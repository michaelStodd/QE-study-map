A substance that has a fixed chemical composition through out is called a **pure substance**. In the liquid phase, a substance that is not about to vaporize is called a **compressed** or **subcooled liquid**. In the gas phase, a sub stance that is not about to condense is called a **superheated vapor**. During a phase-change process, the temperature and pressure of a pure substance are dependent properties. At a given pressure, a substance changes phase at a fixed temperature, called the **saturation temperature**. Likewise, at a given temperature, the pressure at which a substance changes phase is called the **saturation pressure**. During a boiling process, both the liquid and the vapor phases coexist in equilibrium, and under this condition the liquid is called **saturated liquid** and the vapor **saturated vapor**.

In a saturated liquid–vapor mixture, the mass fraction of vapor is called the quality and is expressed as
$$
\chi = \frac{m_{vapor}}{m_{total}}
$$
It has no meaning in the compressed liquid or superheated vapor regions. In the saturated mixture region, the average value of any intensive property $y$ is determined from
$$
y=y_f + \chi y_{fg}
$$
where $f$ stands for saturated liquid and $g$ for saturated vapor

In the absence of compressed liquid data, a general approximation is to treat a compressed liquid as a saturated liquid at the given temperature,
$$
y \approx y_{f@T}
$$
where $y$ stands for $\nu$, $u$, or, $h$.

The state beyond which there is no distinct vaporization process is called the critical point. At supercritical pressures, a substance gradually and uniformly expands from the liquid to vapor phase. All three phases of a substance coexist in equilibrium at states along the triple line characterized by triple-line temperature and pressure. The compressed liquid has lower  $\nu$, $u$, and, $h$ values than the saturated liquid at the same $T$ or $P$. Likewise, superheated vapor has higher $\nu$, $u$, and, $h$ values than the saturated vapor at the same $T$ or $P$. 

Any relation among the pressure, temperature, and specific volume of a substance is called an **equation of state**. The simplest and best-known equation of state is the ideal gas equation of state, given as
$$
P\nu = RT
$$
where $R$ is the gas constant.  Real gases exhibit ideal-gas behavior at relatively low pressures and high temperatures.

The deviation from ideal-gas behavior can be properly accounted for by using the **compressibility factor** $Z$ , defined as
$$
Z = \frac{P\nu}{RT}, \hspace{0.5cm}\text{or} \hspace{0.5cm} \frac{\nu_{actual}}{\nu_{ideal}}
$$
The $Z$ factor is approximately the same for all gases at the same **reduced temperature** and **reduced pressure**, which are defined as
$$
T_R = \frac{T}{T_{cr}}, \hspace{0.5cm}\text{and} \hspace{0.5cm} 
P_R = \frac{P}{P_{cr}}
$$
where $P_{cr}$ and $T_{cr}$ are the critical pressure and temperature, respectively. This is known as the **principle of corresponding states**. When either $P$ or $T$ is unknown, it can be determined from the compressibility chart with the help of the pseudo reduced specific volume, defined as
$$
\nu_R = \frac{\nu_{actual}}{RT_{cr}/P_{cr}}
$$
The $P$-$\nu$-$T$ behavior of substances can be represented more accurately by more complex equations of state. Three of the best known are

* ***van der Vaals**: $(P + \frac{a}{\nu^2})(\nu - b)=RT$
	* $a=\frac{27R^2T^2_{cr}}{64P_cr}$
	* $b=\frac{RT}{8P_{cr}}$
* **Beattie-Bridgeman**: $P=\frac{R_uT}{\bar \nu^2}(1-\frac{c}{\bar \nu T^3})(\bar \nu +B)- \frac{A}{\bar \nu^2}$
	* $A=A_0(1-\frac{a}{\bar \nu})$
	* $B = B_0(1-\frac{b}{\bar \nu})$
* **Benedict-Webb-Rubin**: ***I am not writing this one, lol***
