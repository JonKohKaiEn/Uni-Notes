# Analog vs Digital
| Communication | Description | Pros | Cons |
| ---- | ---- | ---- | ---- |
| Analog | Raw input is sent with little prepreocessing | Little preprocessing of raw input required | Not all types of input can be transmitted |
| Digital | Raw input is converted into bits, then fed to a modulator before being sent | Any input can be converted to digital format | Raw input requires some preprocessing |

# Signal Geometry
- Continuous-time signals can be described as vectors
- Inner product
	- Generalisation of dot product
	- Discrete time: $\large\langle s,r \rangle = \sum\limits_{i=1}^m s[i]r^{*}[i]$
	- Continuous time: $\large\langle s,r \rangle = \int_{-\infty}^{\infty} s(t)r^{*}(t) \: \mathrm{d}t$
	- Orthogonality
		- If $\langle s,r \rangle = 0$ , the signals are orthogonal (at right angles) to each other
		- If signals are orthogonal, they can be split apart easily
	- Signal energy
		- The inner product of a signal with itself
		- $\large E_s = ||s||^2 = \langle s,s \rangle = \int_{-\infty}^{\infty} |s(t)|^2 \: \mathrm{d}t$
- Convolution