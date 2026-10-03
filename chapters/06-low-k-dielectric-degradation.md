# Chapter 6: Ultra-Low-k Dielectric Degradation & Silylation Repair

## 6.1 Demethylation of Carbon-Doped Oxides (SiCOH)
Advanced interconnect dielectrics utilize organosilicate glass ($\text{SiCOH}$) with porosity $>25\%$ to achieve dielectric constants $k \le 2.4$.
- The low dielectric constant relies on terminal hydrophobic methyl groups ($-\text{CH}_3$) terminating the silicon framework.
- During photoresist stripping and etch chemistries, oxygen and fluorine radicals diffuse into the porous network:

$$\equiv\text{Si-CH}_3 + \text{O}^* \to \equiv\text{Si-OH} + \text{CO}_2 + \text{H}_2\text{O}$$

- The loss of methyl groups replaces non-polar bonds with polar silanol ($\equiv\text{Si-OH}$) groups, which absorb atmospheric moisture ($k_{\text{water}} \approx 80$), causing $k$ to surge from $2.4$ to $>3.8$.

## 6.2 Vapor-Phase Silylation Repair
To salvage degraded low-k films, fabs deploy chemical vapor silylation treatments using precursors like Hexamethyldisilazane (HMDS) or Dimethyldichlorosilane (DMDCS):

$$\equiv\text{Si-OH} + (\text{CH}_3)_3\text{Si-NH-Si}(\text{CH}_3)_3 \to \equiv\text{Si-O-Si}(\text{CH}_3)_3 + \text{NH}_3$$

Silylation replaces silanol hydroxyls with bulky trimethylsilyl groups, restoring film hydrophobicity and bringing the dielectric constant back below $2.5$.
