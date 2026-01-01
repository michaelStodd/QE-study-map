
Some thermodynamic properties can be measured directly, but many others cannot. Therefore, it is necessary to develop some relations between these two groups so that the properties that cannot be measured directly can be evaluated. The derivations are based on the fact that properties are point functions, and the state of a simple, compressible system is completely specified by any two independent, intensive properties.

## Gibbs
The equations that relate the partial derivatives of properties $P$, $\nu$, $T$, and $s$ of a simple compressible substance to each other are called the **Maxwell relations**. They are obtained from the four **Gibbs equations**, expressed as

$$
du = Tds - Pd\nu
$$
$$
dh = Tds + \nu dP
$$
$$
da = -sdT - Pd\nu
$$
$$
dg = -sdT + \nu dP
$$


## Maxwell relations
$$
\left(\frac{\partial T}{\partial\nu}\right)_{s} = -\left(\frac{\partial P}{\partial s}\right)_{\nu}
$$
$$
\left(\frac{\partial T}{\partial P}\right)_{s} = \left(\frac{\partial \nu}{\partial s}\right)_{P}
$$
$$
\left(\frac{\partial s}{\partial\nu}\right)_{T} = \left(\frac{\partial P}{\partial T}\right)_{\nu}
$$
$$
\left(\frac{\partial s}{\partial P}\right)_{T} = -\left(\frac{\partial \nu}{\partial T}\right)_{P}
$$

## Clapeyron equation
The **Clapeyron equation** enables us to determine the enthalpy change associated with a phase change from a knowledge of $P$, $\nu$, and $T$ data alone. It is expressed as
$$
\left(\frac{dP}{dT} \right)_{sat} = \frac{h_{fg}}{T\nu_{fg}}
$$
For liquid–vapor and solid–vapor phase-change processes at low pressures, it can be approximated as
$$
ln\left(\frac{P_2}{P_1}\right) \approx \frac{h_{fg}}{R}\left(\frac{T_2-T_1}{T_1T_2}\right)_{sat}
$$
The changes in internal energy, enthalpy, and entropy of a simple compressible substance can be expressed in terms of pressure, specific volume, temperature, and specific heats alone as
$$
du = c_v dT + \left[T\left(\frac{\partial P}{\partial T}\right)_{\nu} - P\right]d\nu
$$
$$
dh = c_p dT + \left[\nu - T\left(\frac{\partial \nu}{\partial T}\right)_{P}\right]dP
$$
$$
ds = \frac{c_v}{T} dT + \left(\frac{\partial P}{\partial T}\right)_{\nu} d\nu
$$
or,
$$
ds = \frac{c_P}{T} dT - \left(\frac{\partial \nu}{\partial T}\right)_{P} dP
$$

## Specific heats
For specific heats, we have the following general relations:
$$
\left(\frac{\partial c_\nu}{\partial \nu}\right)_{T} = T\left(\frac{\partial^2 P}{\partial T^2}\right)_{\nu} 
$$
$$
\left(\frac{\partial c_P}{\partial P}\right)_{T} = -T\left(\frac{\partial^2 \nu}{\partial T^2}\right)_{P} 
$$
$$
c_{p,T} - c_{p0,T} = -T\int_0^P\left(\frac{\partial^2 \nu}{\partial T^2}\right)_{P}dP
$$
$$
c_p-c_\nu = -T\left(\frac{\partial \nu}{\partial T}\right)^2_{P}\left(\frac{\partial P}{\partial \nu}\right)_{T}
$$
$$
c_p-c_\nu = \frac{\nu T\beta^2}{\alpha}
$$
* $\beta = \frac{1}{\nu}\left(\frac{\partial \nu}{\partial T}\right)_P\to$ *volume expansivity*
* $\alpha = \frac{-1}{\nu}\left(\frac{\partial \nu}{\partial P}\right)_T\to$ *isothermal compressibility* 

The difference $c_p - c_\nu$  is equal to <u> R for ideal gases</u> and to <u>zero for incompressible substances</u> 

## Joule-Thomson Coefficient
The temperature behavior of a fluid during a throttling ($h =$ constant) process is described by the **Joule-Thomson coefficient**, defined as
$$
\mu_{JT}=\left(\frac{\partial T}{\partial P}\right)_h
$$The Joule-Thomson coefficient is a measure of the change in temperature of a substance with pressure during a constant enthalpy process, and it can also be expressed as
$$
\mu_{JT} = \frac{-1}{c_p} \left[\nu - T\left(\frac{\partial \nu}{\partial T}\right)_{P}\right]
$$

The enthalpy, internal energy, and entropy changes of real gases can be determined accurately by utilizing *generalized enthalpy* or *entropy departure* charts to account for the deviation from the ideal-gas behavior by using the following relations:
$$
\bar h_2 - \bar h_1 = (\bar h_2 - \bar h_1)_{ideal} - R_uT_{cr}(Z_{h_2}-Z_{h_1})
$$
$$
\bar u_2 - \bar u_1 = (\bar h_2 - \bar h_1) - R_u(Z_2T_2-Z_1T_1)
$$
$$
\bar s_2 - \bar s_1 = (\bar s_2 - \bar s_1)_{ideal} - R_u(Z_{s_2}-Z_{s_1})
$$
where the values of $Z_h$ and $Z_s$ are determined from the generalized charts