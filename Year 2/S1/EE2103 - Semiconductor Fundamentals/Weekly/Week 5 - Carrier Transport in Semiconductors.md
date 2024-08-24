# Drift
- When an electric field is applied across a semiconductor, it can be represented on the energy band diagram by tilting the diagram
- $E_c$ is lower at the higher potential
- The kinetic energy of the electrons is the energy difference between the energy of the electron and $E_c$
- When the electron moves to an area of higher potential (lower $E_c$) , it can lose energy when it bumps into the crystal atoms
	- The energy of the electron will not decrease below $E_c$
	- Electrons in the valence band can gain energy from the collision, allowing it to be in the conduction band (avalanche effect)
- Drift velocity of electrons can be given by $v_{dn} = -\mu_n\xi$ , where $\mu_n = \dfrac{q\tau_{cn}}{m_n^*}$
	- lower $m_n^*$ -> higher $\mu_n$ -> higher $v_{dn}$
	- drift velocity of holes is given by a similar formula
- Effects of impurity concentration on $\mu_n$
	- When donor atoms are ionized, they become positively charged
	- Electrons experience force of attraction from donor atom
- Effects of temperature on $\mu_n$
	- Impurity
		- At low $T$, electrons will be affected more by the forces of attraction from the donor atoms
	- Lattice
		- At high $T$, since the lattice atoms are moving more, the electron has a higher chance of bumping into the lattice atoms
- Drift current density & mobility
	- For electron and holes
		- Drift density: $J_{n,drift} = qn\mu_n\xi = \sigma_n\xi$ (electrons) / $J_{p,drift} = qn\mu_p\xi = \sigma_p\xi$ (holes)
		- Conductivity: $\sigma_n = qn\mu_n$ (electrons) / $\sigma_p = qn\mu_p$ (holes)
		- Resistivity: $\rho_n = \dfrac{1}{\sigma_n}$ (electrons) / $\rho_p = \dfrac{1}{\sigma_p}$ (holes)
	- Total
		- Drift density: $J_{drift} = J_{n,drift} + J_{p,drift} = \sigma\xi$
		- Conductivity: $\sigma = \sigma_n + \sigma_p = qn\mu_n + qp\mu_p$
		- Resistivity: $\rho = \dfrac{1}{\sigma} = \dfrac{1}{qn\mu_n + qp\mu_p}$
# Diffusion
- Current density from diffusion
	- Electrons: $J_{n,diff} = qD_n\dfrac{dn}{dx}$
	- Holes: $J_{p,diff} = -qD_p\dfrac{dp}{dx}$
- Current density from both diffusion and drift
	- Electrons: $J_n = qn\mu_n\xi + qD_n\dfrac{dn}{dx}$
	- Holes: $J_p = qp\mu_p\xi - qD_p\dfrac{dp}{dx}$

# Special Case: Non-uniform Doping
Assuming one side has more dopants
- There will be a concentration gradient -> diffusion current
- There will be an electric field -> drift current
- Material is under thermal equilibrium -> no net current
- $J_{n,drift} + J_{n,diff} = 0$