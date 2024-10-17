# Continuous vs Discrete Time
- Continuous time
	- Denoted $x(t)$
	- Value is specified at all values of $t$
- Discrete time
	- Denoted $x[n]$
	- Value is specified only for integer values of $n$
![[CT vs DT.png]]
# Continuous vs Discrete Value
- Continuous value
	- Amplitude can take on any real value
- Discrete value
	- Amplitude can only take on a finite number of values
![[CV vs DV.png]]
# Deterministic vs Random
- Deterministic
	- Can be mathematically modelled as a function of time
- Random
	- Only known in terms of probabilistic description (e.g. noise)
![[Deterministic vs Random.png]]
# Even vs Odd
- Even signal: $x_{e}(t) = x_{e}(-t)$
	- e.g. Cosine wave
- Odd signal: $x_{o}(t) = -x_{o}(t)$
	- e.g. Sine wave
- Any deterministic signal can be decomposed into sum of an even and odd signal $x(t) = x_{e}(t) + x_{o}(t)$
	- $x_{e} = \frac{1}{2}[x(t)+x(-t)]$
	- $x_{o} = \frac{1}{2}[x(t)-x(-t)]$
- Properties
	- $Even \times Even = Even$
	- $Odd \times Odd = Odd$
	- $Even \times Odd = Odd$
	- $\large \int_{-T_{0}}^{T_{0}} x_{e}(t) \: \mathrm{d}t = 2\int_{0}^{T_{0}} x_{e}(t) \: \mathrm{d}t$
	- $\large \int_{-T_{0}}^{T_{0}} x_{o}(t) \: \mathrm{d}t = 0$
# Periodic vs Aperiodic
- Periodic
	- Signal has a constant period $0 < T_{0} < \infty$ such that $x(t) = x(t+T_{0})$
- Aperiodic
	- Signal does not satisfy the equation
# Energy-Type vs Power-Type
- Energy-type
	- The signal has finite energy ($0<E_x<\infty$)
		- CT: $E_{x}= \int_{-\infty}^{\infty} |x(t)|^{2} \: \mathrm{d}t$
		- DT: $E_{x} = \sum\limits_{n=-\infty}^{\infty} |x[n]|^2$
- Power-type
	- The signal has finite power ($0 < P_{x}< \infty$)
		- CT: $\displaystyle P_{x} = \lim_{T\to\infty} \frac{1}{T} \int_{-\frac{T}{2}}^{\frac{T}{2}} |x(t)|^{2} \: \mathrm{d}t$
		- DT: $\displaystyle P_{x} = \lim_{K \to \infty} \frac{{1}}{{2K+1}} \sum\limits_{n=-K}^{K} |x[n]|^2$
	- If signal is periodic, then power is easier to calculate
		- CT: $P_{x} = \frac{1}{T_0} \int_{t_1}^{t_{1}+T_0} |x(t)|^{2} \: \mathrm{d}t$
		- DT: $P_{x}= \frac{1}{K_{0}} \sum\limits_{n=K}^{k+K_{0-1}} |x[n]|^2$