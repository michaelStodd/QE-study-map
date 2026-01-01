## Definition 

The second law of thermodynamics leads to the definition of a new property called **entropy**, which is a quantitative measure of microscopic disorder for a system. Any quantity whose cyclic integral is zero is a property, and entropy is defined as

$$dS = \left(\frac{dQ}{T}\right)_{int,rev}$$

For the special case of an internally reversible, isothermal process, it gives

$$\Delta S = \frac{Q}{T_0}$$

The inequality part of the Clausius inequality combined with the definition of entropy yields an inequality known as the *increase of entropy principle*, expressed as

$$S_{gen}\ge 0$$

where $S_{gen}$ is the entropy generated during the process. Entropy change is caused by heat transfer, mass flow, and irreversibilities. 
* $\Delta S >0\to$ Heat transfer to a system 
* $\Delta S <0\to$ heat transfer from a system.  
The effect of irreversibilities is always to increase the entropy.

---
## Isentropic relations

The *entropy-change* and *isentropic relations* for a process can be summarized as follows:


### Pure substances

* Any process: $\Delta s = s_2 - s_1$
* **Isentropic process:** $\Delta s = 0$

### Incompressible substances

* Any process: $\Delta s = s_2-s_1=c_{avg}ln\frac{T_2}{T_1}$
* Isentropic process: $T_2 = T_1$

### Ideal gases

* Constant specific heats (approximate treatment):
	* Any process:
		* $\Delta s = c_{v,avg}ln\frac{T_2}{T_1} + R\hspace{0.2cm}ln\frac{\nu_2}{\nu_1}$ 
		* $\Delta s = c_{p,avg}ln\frac{T_2}{T_1} - R\hspace{0.2cm}ln\frac{P_2}{P_1}$ 
	* Isentropic process:
		* $\left(\frac{T_2}{T_1}\right)_{s=const} = \left(\frac{\nu_1}{\nu_2}\right)^{k-1}$
		* $\left(\frac{T_2}{T_1}\right)_{s=const} = \left(\frac{P_2}{P_1}\right)^{(k-1)/k}$
		* $\left(\frac{P_2}{P_1}\right)_{s=const} = \left(\frac{\nu_1}{\nu_2}\right)^{k}$ 

---
## Work
The *steady-flow work* for a reversible process can be expressed in terms of the fluid properties as

$$w_{rev}= -\int \nu dP - \Delta ke - \Delta pe$$

For *incompressible substances* ($\nu =$ constant) it simplifies to

$$w_{rev} = -\nu(P_2 - P_1) - \Delta ke - \Delta pe$$

The work done during a steady-flow process is proportional to the specific volume. Therefore, $\nu$ should be kept as small as possible during a compression process to minimize the work input and as large as possible during an expansion process to maximize the work output.

### Compressor

The reversible work inputs to a compressor compressing an ideal gas from $T_1$, $P_1$ to $P_2$ in an isentropic ($P\nu^k=$ constant), polytropic ($P\nu^n =$ constant), or isothermal ($P\nu =$ constant) manner, are determined by integration for each case with the following results:

$$\text{Isentropic: } w_{comp,in} =\frac{kR(T_2-T_1)}{k-1}=\frac{kRT_1}{k-1}\left[\left(\frac{P_2}{P_1}\right)^{(k-1)/k} -1 \right]$$

$$\text{Polytropic: } w_{comp,in} =\frac{nR(T_2-T_1)}{n-1}=\frac{nRT_1}{n-1}\left[\left(\frac{P_2}{P_1}\right)^{(n-1)/n} -1 \right]$$

$$\text{Isothermal: } w_{comp,in} = RT\hspace{0.1cm}ln\frac{P_2}{P_1}$$

The work input to a compressor can be reduced by using multistage compression with intercooling. For maximum savings from the work input, the pressure ratio across each stage of the compressor must be the same.

---
## Efficiency 
Most steady-flow devices operate under adiabatic conditions, and the ideal process for these devices is the isentropic process. The parameter that describes how efficiently a device approximates a corresponding isentropic device is called **isentropic** or **adiabatic efficiency**. It is expressed for turbines, compressors, and nozzles as follows:

$$\eta_T = \frac{\text{Actual turbine work}}{\text{Isentropic turbine work}} = \frac{w_a}{w_s}\approx \frac{h_1-h_{2a}}{h_1-h_{2s}}$$

$$\eta_C = \frac{\text{Isentropic compressor work}}{\text{Actual compressor work}} = \frac{w_s}{w_a}\approx \frac{h_{2s}-h_1}{h_{2a}-h_1}$$

$$\eta_N = \frac{\text{Actual KE at nozzle exit}}{\text{Isentropic KE at nozzle exit}} = \frac{V_{2a}^2}{V_{2s}^2}\approx \frac{h_1-h_{2a}}{h_1-h_{2s}}$$

In the relations above, $h_{2a}$ and $h_{2s}$ are the enthalpy values at the exit state for actual and isentropic processes, respectively.

---
## Entropy Ballance 

The entropy balance for any system undergoing any process can be expressed in the general form as

$$S_{in} - S_{out} + S_{gen} = \Delta S_{sys}$$

For a general *steady-flow process* it simplifies to 

$$\dot S_{gen} = \sum \dot m_e s_e - \sum \dot m_is_i - \sum \frac{\dot Q_k}{T_k}$$