# Baseband and Passband
- Passband ($S_p(f)$)
	- Narrow range of frequencies centred around a high frequency
	- Can be complex-valued
- Baseband ($S_b(f)$)
	- Range of frequencies centred around 0
	- Can be complex-valued
	- Used to represent passband signals
- Complex-valued signals can be thought of as 2 real-valued signals (complex envelope)
	- $\large s(t) = s_{real}(t) + j \cdot s_{img}(t)$
- Passband can be represented by $s_p(t) = \sqrt{2}s_c(t)cos(2\pi f_c t) - \sqrt{2}s_s(t)sin(2\pi f_c t)$
	- $s_c(t)$ : Cosine component
	- $s_s(t)$ : Sine component
	- $f_c$ : Reference frequency
- Passband can be converted to baseband
	- Throw out negative frequency part
	- Move to the left by $f_c$
	- Scale by $\sqrt{2}$
	- Operations can be reversed to get back the passband

# Encoding Information
- The components can be thought of as being orthogonal
- We can then decompose the signal into $s_c$ ad $s_s$
