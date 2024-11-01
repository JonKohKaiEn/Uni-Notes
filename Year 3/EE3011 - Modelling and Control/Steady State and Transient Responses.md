In time domain analysis, we apply a reference input signal to a system and evaluate the system's response in the time domain

For a stable system, the total time response $y(t) = y_{t}(t) + y_{ss}(t)$
- $y_{t}(t)$ : Transient Response
	- Should be as short as possible
- $y_{ss}(t)$ : Steady-state response
	- Follow the input signal as close as possible
# Test Signals
| Name      | Function                                                          | Notes                     |
| --------- | ----------------------------------------------------------------- | ------------------------- |
| Impulse   | $a\delta (t)$                                                     |                           |
| Step      | $au(t)$                                                           |                           |
| Ramp      | $at \: \text{when} \: t \ge 0$, $0 \: \text{when} \: t \lt 0$     | Integral of step function |
| Parabolic | $at^{2} \: \text{when} \: t \ge 0$, $0 \: \text{when} \: t \lt 0$ | Integral of ramp function |
# 1st Order Systems
- Examples
	- RC circuit
	- Thermal system
	- Pneumatic system
- Unit-step response
	- $\large r(t) = u(t) \rightarrow R(s) = \frac{1}{s}$
	- $\large Y(s) = \frac{1}{\tau s + 1} \frac{1}{s} = \frac{1}{s}-\frac{\tau}{\tau s + 1}$
	- $\large y(t) = 1 - e^{\frac{t}{\tau}}, \text{where} \: t \ge 0$
	- $\tau$ is the time constant