# Chapter 5: Plasma-Induced Damage (PID): Charging & VUV Radiation

## 5.1 Antenna Ratio & Fowler-Nordheim Stress
During metal etching, conductive interconnect lines act as antennas collecting RF charge from plasma density non-uniformities.
- The collected charge drains through the gate electrode to ground, establishing an intense electric field ($>10\text{ MV/cm}$) across the gate oxide:

$$J_{\text{FN}} = A E_{\text{ox}}^2 \exp\left(-\frac{B}{E_{\text{ox}}}\right)$$

- When the **Antenna Area Ratio** ($A_{\text{metal}} / A_{\text{gate}}$) exceeds critical thresholds ($>500:1$), severe Fowler-Nordheim tunneling stress generates bulk oxide traps and breaks $\text{Si-O}$ bonds, triggering early dielectric breakdown (TDDB).

## 5.2 Vacuum Ultraviolet (VUV) Radiation Damage
Plasmas generate intense radiation in the VUV spectrum ($60\text{–}150\text{ nm}$, photon energies $8\text{–}20\text{ eV}$):
- VUV photons exceed the bandgap of $\text{SiO}_2$ ($8.9\text{ eV}$) and low-k dielectrics.
- Photo-ionization creates electron-hole pairs. Electrons are swept out while low-mobility holes are trapped at the $\text{Si/SiO}_2$ interface, increasing interface trap density ($\Delta D_{it}$) and degrading transistor subthreshold slope.
