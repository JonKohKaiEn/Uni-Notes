- At thermal equilibrium, rate of generation = rate of recombination
- At non-equilibrium (e.g. when light is shone on the semiconductor), this is not the case
	- electrons can be bumped up to conduction band , leaving holes in the valence band
	- $n = n_0 + \Delta n$ , $p = p_0 + \Delta p$
	- $np = (n_0 + \Delta n)(p_0 + \Delta p) > n_i^2$
	- 2 Quasi-Fermi levels will be formed, $E_{Fn}$ and $E_{Fp}$
- Low-level injection condition: Steady-state excess carrier density is <10% of majority carrier density
	- $\Delta n_{ss} \leq 0.1n_0$

# Continuity Equation

$\huge\frac{\partial n}{\partial t} A dx = \left|\frac{J_n(x)A}{-q} - \frac{J_n(x+dx)A}{-q}\right| + (G_L - R)Adx$

- $\large\frac{\partial n}{\partial t} A dx$ : Within the region of interest, how does electron density change over time?
- $\large\frac{J_n(x)A}{-q}$ : How many electrons are entering the region?
- $\large\frac{J_n(x+dx)A}{-q}$ : How many electrons are leaving the region?
- $G_L$ : Generation rate
- $R$ : Recombination rate
The equation can be simplified to:
$\huge\frac{\partial n}{\partial t} = \frac{1}{q} \frac{\partial J_n}{\partial x} + G_L - \frac{\Delta n}{\tau_n}$


