# Graphical Approach
![[Diode analysis eg.png]]
- For $V_{DD} >> 0.5V$
	- $\large I_{D} = I_{S}e^{\frac{v_D}{nV_{T}}}$
	- By KVL, $\large I_{D} = \frac{{V_{DD}-V_{D}}}{{R}}$
![[Graphical analysis.png]]
# Iterative Approach
![[Iterative eg.png]]
- Get $V_{TH} = 6V, R_{TH} = 5\mathrm {k}$
- Try an initial value of $V_{D}$ (e.g. 0.7V) and substitute into $I_{D} = \frac{V_{TH}-V_{D}}{R_{TH}}$ to get value of $I_{D}$
- Use $V_{D} = 2V_{T}ln\frac{I_{D}}{I_{S}}$ to get new value of $V_{D}$
- Repeat iteration until values converge (generally 3 d.p.)