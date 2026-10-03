# Chapter 2: Physical Sputtering Thresholds & Cascade Physics

## 2.1 The Threshold Energy for Sputtering ($E_{\text{th}}$)
Physical sputtering cannot occur unless the incident ion transfers kinetic energy exceeding the threshold energy $E_{\text{th}}$:

$$E_{\text{th}} = \frac{U_0}{\gamma (1 - \gamma)}$$

Where:
- $U_0$ = Surface binding energy (sublimation energy $\approx 4.63\text{ eV}$ for silicon)
- $\gamma = \frac{4 m_i m_t}{(m_i + m_t)^2}$ = Energy transfer coefficient between ion of mass $m_i$ and target atom of mass $m_t$

For $\text{Ar}^+$ ions ($40\text{ amu}$) striking silicon ($28\text{ amu}$), $\gamma \approx 0.968$, resulting in a physical sputtering threshold of **$E_{\text{th}} \approx 20\text{–}25\text{ eV}$**.

## 2.2 Sigmund Sputtering Yield Formulation
At energies above threshold ($E > E_{\text{th}}$) in the linear cascade regime, the sputtering yield $Y(E)$ (atoms ejected per incident ion) follows Sigmund's formulation:

$$Y(E) = \frac{0.042 \, \alpha \, S_n(E)}{U_0} \left[ 1 - \sqrt{\frac{E_{\text{th}}}{E}} \right]$$

Where:
- $S_n(E)$ = Nuclear stopping cross-section
- $\alpha$ = Dimensionless correction factor dependent on mass ratio $m_t / m_i$

## 2.3 Angular Dependence of Sputtering ($Y(\theta)$)
Sputter yield peaks at non-normal incidence angles ($\theta \approx 50^\\circ\text{–}65^\\circ$ relative to surface normal) because collision cascades develop closer to the surface, making it easier for target atoms to overcome $U_0$ and escape. This angular dependence causes facetting on mask corners and micro-trenching at trench bottoms.
