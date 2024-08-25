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
For ideal op-amp with negative feedback,
$$\large v_{\epsilon} = v_{-} - v_{+} = 0$$
Since
$$ \large
I_{-} = I_{+} = 0,
v_{\epsilon} = 0,
R_{in} = \infty,
$$

- For ideal op-amp with negative feedback, $v_{\epsilon} = v_{-} - v_{+} = 0$
- Since $I_{-} = I_{+} = 0$ , $v_{\epsilon} = 0$ , $R_{in} = \infty$
	- $v_{+} = v_{-}$
	- Since positive terminal is connected to ground, $v_{+} = 0$
	- Therefore, $v_{-} = 0$
- $\large I_{R_{1}} = \frac{v_{in} - v_{-}}{R_{1}}$
	- Since $I_{-} = 0$ , $I_{R_{2}} = I_{R_{1}}$
	- $\large I_{R_{2}} = \frac{v_{-} - v_{out}}{R_{2}}$
	- Therefore, 