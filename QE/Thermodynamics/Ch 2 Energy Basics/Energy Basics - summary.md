 **Internal Energy:** molecular energy of a system and may exist in sensible, latent, chemical, and nuclear forms

**Mass flow rate** 
$$
\dot m = \rho \dot \nu =\rho A_c V_{avg}
$$
* $\rho\to$ density
* $\dot\nu\to$ volume flow rate
* $A_c\to$ Cross sectional area
* $V_{avg}\to$ Average velocity normal to $A_c$

**Energy flow rate** is given in a similar manor to total anergy $E$
$$
\dot E=\dot m e
$$
**Mechanical Energy:** the form of energy that can be converted to mechanical work completely and directly by a mechanical device such as an ideal turbine. 
$$
e_{mech} = \frac{P}{\rho} + \frac{V^2}{2} + gz
$$
* It is expressed on a unit mass basis
* $P/\rho \to$ *flow energy* per unit mass; pressure over density
* $V^2/2\to$ *kinetic energy* per unit mass; V is velocity
* $gz\to$ *potential energy* per unit mass; gravitational acceleration times height

Energy can cross the boundaries of a closed system in the form of heat or work. For control volumes, energy can also be transported by mass. If the energy transfer is due to a temperature difference between a closed system and its surroundings, it is **heat**; otherwise, it is **work**.

Work is the energy transferred as a force acts on a system through a distance. Various forms of work are expressed as follows:
* **Electrical Work:** $W_e = V I d t$
	* $V$: potential difference
	* $I$: current
* **Shaft work:** $W_{sh} = 2\pi nT$
	* $T:$ torque
	* $n:$ revolutions
* **Spring work** $W_{spring} = kx d x$ 

The *first law of thermodynamics* is essentially an expression of the *conservation of energy* principle, also called the energy balance. The general mass and energy balances for any system undergoing any process can be expressed as
$$
\Delta E_{system} = E_{in} - E_{out}
$$

The efficiencies of various devices are defined as 
$$
\eta = \frac{E_{out}}{E_{in}}
$$
* Pump: receives shaft work and transfers it to the fluid $\eta_{pump} = \frac{\Delta \dot E_{mech,fluid}}{\dot W_{shaft,in}}$
* Turbine: converts the mechanical energy of a fluid to shaft work $\eta_{turb} = \frac{\dot W_{shaft,out}}{|\Delta \dot E_{mech,fluid}|}$

A similar relationship follows for an electrical system
* Motor: converts electrical energy to rotating mechanical energy $\eta_{mot} = \frac{\dot W_{shaft,out}}{\dot W_{elect,in}}$
* Generator: converts rotating mechanical energy to electrical energy $\eta_{gen} = \frac{\dot W_{elect,out}}{\dot W_{shaft,in}}$

Combined, or overall efficiencies, multiply
* $\eta_{pump/motor} = \eta_{pump}\eta_{motor}=\frac{\Delta \dot E_{mech,fluid}}{\dot W_{elect,in}}$
* 