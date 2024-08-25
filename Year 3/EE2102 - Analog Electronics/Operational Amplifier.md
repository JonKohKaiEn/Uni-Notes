# Parts of an Op-Amp
- Inverting input
- Non-inverting input
- Output
- $V_{DD}$ or $V_{CC}$, $V_{SS}$ or $V_{EE}$ (not usually included)

# Ideal Op-Amp
## Properties
- Voltage gain (Open Loop) $A_{vOL} = \infty$
	-  The output voltage is bound by $V_{DD}$ and $V_{SS}$
- Input resistance $R_{in} = \infty$
	- Resistance between the two inputs
- $I_{bias} = I_{+} = I_{-} = 0$
	- Virtual open
- Output resistance $R_{out} = 0$
- Bandwidth $BW = \infty$
- Slew rate $\frac{dV_{out}}{dt} = SR = \infty$
	- No delay between input and output
## Feedback
Only negative feedback is tested in the course :)
- The feedback will always go into the inverting input
### Non-inverting Gain Amplifier

### Inverting Gain Amplifier
![[Pasted image 20240825215858.png]]
$$
A_{vCL} = \frac{v_{out}}{v_{in}} = - \frac{R_{2}}{R_{1}}
$$
