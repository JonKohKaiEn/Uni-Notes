# Density of States and Fermi-Dirac Statistics
- Knowing the number of electrons in $E_c$ is important since it determines the conductivity of the semiconductor
- We can estimate it using 2 values
	- Density of States (DOS) -> number of seats in a certain category of a concert
	- Fermi-Dirac statistics (FD) -> probability of finding someone in that category
	- $n_0=\int_{E_c}^\infty DOS\times FD \: \mathrm{d}E$
- Density of States 
	- Number of states per unit energy and per unit volume ($J^{-1}m^{-3}$)
	- $g_c(E)$ for conduction band, $g_v(E)$ for valence band
	- $g_c(E) = \dfrac{4\pi(2m_n^*)^{3/2}}{h^3}\sqrt{E-E_c}$ 
		- use $m_p^*$ for $g_v(E)$
- Fermi-Dirac Statistics
	- Probability of finding an electron at a energy level
	- Fermi Level $E_f$ : Energy level where the probability of finding an electron is 50%
	- $f(E)=\dfrac{1}{1+exp\left[\dfrac{E-E_f}{kT}\right]}$
	- When temperature $T$ increases, graph of $f(E)$ stretches along $E$ -> probability of finding an electron at a higher $T$ increases
	- When semiconductor is doped, $E_f$ shifts to a higher energy

# Carrier Modelling in Energy Band Diagram
- $n_0 = N_ce^{-(E_c-E_f)/kT}$
	- $N_c$ : (Effective) Total number of states at $E_c$
	- $e^{-(E_c-E_f)/kT}$ : Probability of finding electron at $E_c$
	- All of the states in the conduction band have been squeezed into $E_c$

# Carrier Modelling for Intrinsic Semiconductors
- For intrinsic materials, $E_f = E_i$ 
- With derivation, some equations can be formed
	- $n_i = \sqrt{N_cN_v}e^{E_g/{2kT}}$
		- At a certain $T$, $n_i$ will be constant
		- $n_i$ is larger for smaller $E_g$
	- $n_0p_0 = n_i^2$
		- $n_0p_0$ is always constant regardless of doping concentration
	- $E_i = E_{mid} + \dfrac{3}{4}kTln\left(\dfrac{m_p^*}{m_n^*}\right)$
		- $E_i$ will be in the middle of the band gap if $m_p^* = m_n^*$

# Carrier Modelling for Extrinsic Semiconductors
- At equilibrium, the charge must be neutral
	- $n_0 + N_A^- = p_0 + N_D^+$
		- Using $n_0p_0 = n_i^2$ , we get $p_0 = \dfrac{(N_A^- - N_D^+)+\sqrt{(N_A^- - N_D^+)^2+4n_i^2}}{2}$
		- Similar equation for $n_0$