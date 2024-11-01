# Linear Modulation
- Previously, information was represented in bits ($b_k$), where $b_k \in \{1,0\}$
- We can generalise the linear modulation formula by making $b_k$ a complex number
	- $b_k = b_c + jb_s = re^{j\theta}$
- $b_k$ can then be fed into a linear modulator, where $s(t) = \sum\limits_{k=-\infty}^{\infty} b_k \cdot p(t-kT)$
- We need a mapper to convert our normal bits (1, 0) into a sequence of complex numbers
- Constellations
	- Constellations are a way to map bits to complex signals
	- Some constellations can map multiple bits to one complex signal
		- Downside: More points -> Higher density of points -> Detector cannot reliably distinguish points (especially with noise)
		- Points further away from the origin require a higher power & energy to transmit
		- The squared distance of the point $b_k$ from the origin ($||b_k||^2$) is the energy required to send the signal
- Bandwidth
	- Since the bits that we are sending ($b_k$) is stochastic, we cannot just take the fourier transform of $s(t)$
	- For $s(t)$ with uncorrelated points of zero mean, the Power Spectral Density $\large S_u(f) = \frac{E[|b_k|^2]}{T} |p(f)|^2$
- We need to figure out:
	- How to choose the mapper
	- How to choose the pulse
	- How to design the detector

# Signal Shapes
- $sinc(x)$ extends infinitely in both directions
	- Pulse can be cut off, but there are other problems
- When multiple pulses are sent, we can pick out the pulses by sampling in intervals
	- However, we cannot ensure that our receiver and transmitter are synchronised, resulting in self-interference or inter-symbol interference (ISI)
		- One reason is that it decays relatively slowly ($\frac{1}{x}$)
- We can also use $sinc^2(x)$
	- Decays faster than $sinc(x)$ 
		- Decays with $\frac{1}{x^2}$
	- Downside is that it has a higher bandwidth than $sinc(x)$
- Raised cosine
	- Decays faster than $sinc^2(x)$
		- Decays with $\frac{1}{x^3}$
	- Uses slightly more bandwidth than $sinc(x)$