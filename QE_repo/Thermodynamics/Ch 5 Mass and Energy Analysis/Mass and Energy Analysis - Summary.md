
The amount of mass flowing through a cross section per unit time is called the **mass flow rate**, and is expressed as
$$
\dot m = \rho V A
$$
* $\rho=$ density of fluid
* $V=$ velocity of fluid
* $A=$ cross sectional area normal to flow direction
The volume of the fluid flowing through a cross section per unit time is called the *volume flow rate and is expressed as
$$
\dot\nu = VA = \dot m/\rho
$$
* $\nu=$ volume 

The work required to push a unit mass of fluid into or out of a control volume is called *flow work* or *flow energy*, and is expressed as $w_{flow} = P\nu$. In the analysis of control volumes, it is convenient to combine the flow energy and internal energy into **enthalpy**. Then the total energy of a flowing fluid is expressed as
$$
\theta = h + ke + pe = h + \frac{V^2}{2} + gz
$$
The total energy transported by a flowing fluid of mass $m$ with uniform properties is $m\theta$. The rate of energy transport by a fluid with a mass flow rate of $\dot m$ is $\dot m\theta$. When the kinetic and potential energies of a fluid stream are negligible, the amount and rate of energy transport become $E_{mass}= mh$ and $\dot E_{mass}= \dot m  h$, respectively.

The *first law of thermodynamics* is essentially an expression of the conservation of energy principle, also called the energy balance. The general mass and energy balances for any system undergoing any process can be expressed as $\Delta E = E_{in} - E_{out}$

Thermodynamic processes involving control volumes can be considered in two groups: 
* <u>steady-flow processes</u>: the fluid flows through the control volume steadily, experiencing no change with time at a fixed position. The mass and energy content of the control volume remain constant during a steady-flow process. Taking heat transfer to the system and work done by the system to be positive quantities, the conservation of mass and energy equations for steady-flow processes are expressed as 
$$
\dot m_{sys} = 0
$$
$$
\dot Q - \dot W = \sum_{out}\dot m(h+\frac{V^2}{2}+gz) - \sum_{in}\dot m(h+\frac{V^2}{2}+gz)
$$
	* General forms of the equations for steady-flow processes for single-stream (one-inlet–one-exit) systems such as nozzles, diffusers, turbines, compressors, and pumps, are given by
$$
\dot m_1 = \dot m_2 \to \frac{V_1 A_1}{\nu_1} =\frac{V_2 A_2}{\nu_2} 
$$
$$
\dot Q - \dot W = \dot m\left(h_2 - h_1+\frac{V_2^2-V_1^2}{2}+g(z_2 - z_1)\right)
$$
* <u>unsteady-flow processes</u>: Most unsteady-flow processes can be modeled as a uniform-flow process, which requires that the fluid flow at any inlet or exit is uniform and steady, and thus the fluid properties do not change with time or position over the cross section of an inlet or exit. If they do, they are averaged and treated as constants for the entire process. When kinetic and potential energy changes associated with the control volume and the fluid streams are negligible, the mass and energy balance relations for a uniform-flow system are expressed as
$$
\dot m \neq 0
$$
$$
Q-W = \sum_{out}mh - \sum_{in}mh + (m_2u_2 - m_1u_1)_{sys}
$$

When solving thermodynamic problems, it is recommended that the general form of the energy balance $\Delta E$ be used for all problems, and simplify it for the particular problem instead of using the specific relations given here for different processes.