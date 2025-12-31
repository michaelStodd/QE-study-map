Work is the energy transferred as a force acts on a system through a distance. The most common form of mechanical work is the **boundary work**, which is the work associated with the expansion and compression of substances. On a $P$-$\nu$ diagram, the area under the process curve represents the boundary work for a quasi-equilibrium process. Various forms of boundary work are expressed as follows:

1. General: $W_b = \int_1^2Pd\nu$
2. *Isobaric*: $W_b=P_o(\nu_2 - \nu_1)$ 
	1. $P_0=const$
3. *Polytropic*: $W_b = \frac{P_2\nu_2 - P_1\nu_1}{1-n}$ 
	1. $n\ \neq 1$
	2. $P\nu^n = const$
4. *Isothermal*: $W_b = P_1\nu_1 ln\frac{\nu_2}{\nu_1}$
	1. $P_1\nu_1 = mRT_0 = const$

Taking heat transfer *to* the system and work done *by* the system to be positive quantities, the energy balance for a closed system can also be expressed as
$$
Q - W = \Delta U + \Delta KE + \Delta PE
$$
where
* $W =W_{other} + W_b$
* $\Delta U = m(u_2- u_1)$
* $\Delta KE = \frac{m}{2}(V^2_2 - V^2_1)$
* $\Delta PE = mg(z_2 - z_1)$

For a *constant-pressure process* $W_b + \Delta U = \Delta H$. Thus,
$$
Q - W_{other} = \Delta H + \Delta KE + \Delta PE
$$

The amount of energy needed to raise the temperature of a unit mass of a substance by one degree is called the specific heat at constant volume $c_v$ for a constant-volume process and the **specific heat** at *constant pressure* $c_p$ for a constant pressure process. They are defined as
$$
c_v = \left(\frac{\partial u}{\partial T}\right)_v \hspace{0.5cm} \text{and} \hspace{0.5cm} c_p = \left(\frac{\partial h}{\partial T}\right)_p
$$
For ideal gases $u$, $h$, $c_v$, and $c_p$ are functions of temperature alone. The $\Delta u$ and $\Delta h$ of ideal gases are expressed as
$$
\Delta u = u_2 - u_1 = \int_1^2 c_v(T)dT \approx c_{v,avg}(T_2 - T_1)
$$
and
$$
\Delta h = h_2 - h_1 = \int_1^2 c_p(T)dT \approx c_{p,avg}(T_2 - T_1)
$$

For ideal gases, $c_v$ and $c_p$ are related by
$$
c_p = c_v +R
$$
where $R$ is the gas constant. The *specific heat ratio $k$* is defined as
$$
k = \frac{c_p}{c_v}
$$
For incompressible substances (liquids and solids), both the constant-pressure and constant-volume specific heats are identical and denoted by $c=c_p=c_v$. Moreover, for an incompressible substance

$$
\Delta u = \int_1^2 c(T)dT \approx c_{avg}(T_2 - T_1)
$$
and
$$
\Delta h = \Delta u + \nu\Delta P
$$
