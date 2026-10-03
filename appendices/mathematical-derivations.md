# Appendix B: Mathematical Derivations

## B.1 Sigmund Sputtering Threshold Derivation
In a head-on binary elastic collision between an incident ion of mass $m_1$ and kinetic energy $E_0$ and a stationary target atom of mass $m_2$, the maximum energy transferred $T_{\text{max}}$ is:

$$T_{\text{max}} = \gamma E_0, \quad \text{where } \gamma = \frac{4 m_1 m_2}{(m_1 + m_2)^2}$$

For physical sputtering to occur:
1. The target atom must be displaced from its lattice site (requiring displacement energy $E_d \approx 15\text{ eV}$ in silicon).
2. Through subsequent collisions, a recoil atom must be redirected toward the surface and arrive with energy exceeding surface binding energy $U_0$ ($4.63\text{ eV}$ for $\text{Si}$).

Detailed kinematics show that for normal incidence, the recoil atom must reverse direction via at least two collisions, establishing the theoretical threshold energy:

$$E_{\text{th}} = \begin{cases}
\frac{U_0}{\gamma (1 - \gamma)}, & \text{for } m_1 / m_2 \le 1 \\
\frac{8 U_0 (m_1 / m_2)^{2/5}}{\gamma}, & \text{for } m_1 / m_2 > 1
\end{cases}$$

## B.2 Fluorocarbon Layer Steady-State Mass Balance
Consider a fluorocarbon polymer layer of thickness $L_p$ and atomic density $\rho_p$ on a substrate.
The time rate of change of polymer thickness is governed by the mass balance:

$$\rho_p \frac{d L_p}{dt} = J_{\text{dep}} - J_{\text{etch}}$$

Where:
- $J_{\text{dep}} = S_{\text{stick}} \cdot \Gamma_{\text{CF}_x}$ is the polymer deposition flux ($S_{\text{stick}}$ is the sticking coefficient, $\Gamma_{\text{CF}_x}$ is radical flux).
- $J_{\text{etch}} = Y_p(E) \cdot \Gamma_{\text{ion}} + k_{\text{chem}} \Gamma_O$ is the polymer consumption flux ($Y_p(E) \propto \sqrt{E_{\text{ion}} - E_{\text{th}}}$ is the ion sputtering yield, $\Gamma_O$ is oxygen radical flux).

In steady state ($\frac{dL_p}{dt} = 0$):

$$L_p = L_0 \ln\left( \frac{J_{\text{dep}}}{J_{\text{etch}}} \right)$$

When $J_{\text{dep}} > J_{\text{etch}}$, $L_p$ grows continuously (net deposition regime); when $J_{\text{dep}} < J_{\text{etch}}$, $L_p$ thins down to sub-nanometer levels, allowing underlying substrate etching.

## B.3 Fowler-Nordheim Tunneling Current Derivation
Under strong electric field $E_{\text{ox}}$, the triangular potential barrier for electrons in the conduction band of silicon facing $\text{SiO}_2$ has width:

$$x_t = \frac{\Phi_B}{E_{\text{ox}}}$$

Using the WKB approximation, the transmission probability $T$ through the triangular barrier is:

$$T = \exp\left( -2 \int_0^{x_t} \sqrt{\frac{2m^*}{\hbar^2} (\Phi_B - e E_{\text{ox}} x)} \, dx \right) = \exp\left( -\frac{4\sqrt{2m^*}\Phi_B^{3/2}}{3e\hbar E_{\text{ox}}} \right)$$

Multiplying by the incident electron flux yields the classic Fowler-Nordheim current density:

$$J_{\text{FN}} = \frac{e^3 E_{\text{ox}}^2}{8\pi h \Phi_B} \exp\left( -\frac{8\pi\sqrt{2m^*}\Phi_B^{3/2}}{3eh E_{\text{ox}}} \right) \equiv A E_{\text{ox}}^2 \exp\left(-\frac{B}{E_{\text{ox}}}\right)$$
