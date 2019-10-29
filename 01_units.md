## SI system of units
The **International System of Units** (**SI**, abbreviated from the French is the modern form of the metric system, and is the most widely used system of measurement. It comprises a coherent system of units of measurement built on seven *base units* (ampere, kelvin, second, meter, kilogram, candela).

### Elementary mechanic units

Wouldn't it be nice to reduce this 7 units? An intention was made to express all units in two base units, **meter** and **seconds**. During the elaboration of this work it came clear that there are some inconsistencies. The main reason for this research was to find the source of the magnetic constant $\mu_0$ ( which has the value $10^{-7}$). 

The kilogram is a physical object which is used to express mass, basically related to the weight of matter. Let's start with the unit of the kilogram. To start it's not common to use a metric prefix as a unit. (one can not say a kilo-kilogram to express 1000 kg). Therefore it's more convenient to start with the gram instead of kilogram. 

Each type of matter has a definition of density which is used to convert a volume of matter to an expression of mass.

The gram, 1/1000 of a kilogram, was provisionally defined in 1795 as the mass of one cubic centimeter of water at the melting point of ice. The final kilogram, manufactured as a prototype in 1799 and from which the IPK was derived in 1875, had a mass equal to the mass of 1 $dm^3$ of water at its maximum density, approximately 4 °C.

All definitions of density of matter are related to this definition. $1 g = 1 cm^3$.

The density of water is expressed as: 

>$\rho_{water} = \frac{1g}{1cm^3} = 1 [\frac{g}{cm^3}]$

The densities of other type of matter are defined in relation to this initial definition. for example, lead has a density which is 11.34 times higher than this of water. 

>$\rho_{lead} = 11.34[\frac{g}{cm^3}]$

This factor can be used to do a revese calculation, every mass can be converted to a volume expressed in $m^3$

>$\rho_{water}=1[\frac{g}{m^3}] = 10^3 [\frac{kg}{m^3}]$

A volume of water can be converted to a mass, but the opposite is also true. A mass of water can be converted to a volume.

>$1 kg_{water}= \frac{1 kg}{\rho_{water}}= 10^{-3} [m^3]$

If the kind of matter is known, mass can be converted in a volume. With this knowledge the other units can be reconstructed.

First of all **Force** 

>$F=m.a [N]$  with $N  \rightarrow \frac{kg.m}{s^2}$ 

will become with the conversion of $kg$ to $m^3$:

>$N \rightarrow \frac{m^3.m}{s^2} \rightarrow \frac{m^4}{s^2}$

The unit of force in the new system will become $[\frac{m^4}{s^2}]$

This will have its impact on all other units derived from force. **Work** is  the base formula of energy 

The SI unit of work is the **Joule**  [J], which is defined as the work expended by a **Force**  of one newton through a displacement of one **meter**. Or in a formula:

>$W=F.s​$ 
>$J \rightarrow [Nm] \rightarrow [\frac{m^4}{s^2}.m] \rightarrow [\frac{m^5}{s^2}]$
>$E_k=\frac{m.v^2}{2} \rightarrow [J] \rightarrow [m^3 (\frac{m}{s})^2] \rightarrow [\frac{m^5}{s^2}]$ 

temperature ==> energy

>$p=\frac{F}{A} \rightarrow [Pa] \rightarrow [\frac{m^4}{s^2}\frac{1}{m^2}] \rightarrow [\frac{m^2}{s^2}]$
>$T= \frac{p.V}{nR} \rightarrow [K] \rightarrow [\frac{m^2}{s^2}.m^3] \rightarrow [\frac{m^5}{s^2}]$

Looking at this, **temperature T** is nothing more or less than **energy E**.

### Electrical units

The start of the use of electrical units can be found in the 19e century. All units were related to the commonly accepted mechanical units, and therefore the electrical units have to be adapted to fit in the mechanical unit system.

As base for this conversion the **cgs system** (centimeter gram second) was used. The history of this system goes back to 1831 but since the international adoption of the MKS standard in the 1940s and the SI standard in the 1960s, the technical use of CGS units has gradually declined worldwide. 

The unit of resistance in the C.G.S. magnetic system was so small (one-billionth of an ohm) that it was considered unfit for practical use and a unit $10^9$ times greater than the C.G.S. unit was selected as of convenient magnitude. This decision was made by the B.A. in 1861.

An intention was made to convert all SI-units to their corresponding ms-units. The electric constant $k_e$ is used to define the relation 

>  $k_e = k_m.c^2 = 10^{-7}.8.9875243264e^{16} [\frac{m^2}{s^2}] = 8987524326.4 [\frac{m^2}{s^2}]$
>
>  in this formula the magnetic factor $k_m$ is a scalar equal to $10^{-7}$.
>
>  $\frac{1}{k_e}= 1.1126534557048096e^{-10} [\frac{s^2}{m^2}]$



| description                |        SI-unit         |            ms-unit             | remarks                      |
| -------------------------- | :--------------------: | :----------------------------: | ---------------------------- |
| Force  ($F=m.a$)           |          1 N           |      1 $\frac{m^4}{s^2}$       | volume depends on the matter |
| Work ($W=F.d$)             |          1 J           |      1 $\frac{m^5}{s^2}$       |                              |
| Power ($P=F.v$)            |          1 W           |      1 $\frac{m^5}{s^3}$       |                              |
| Pressure $(p=\frac{F}{A})$ | 1 Pa $[\frac{N}{m^2}]$ |      1 $\frac{m^2}{s^2}$       |                              |
| Voltage                    |          1 V           |      1 $(\frac{1}{k_e})m$      |                              |
| Electric Field E           |    1 $\frac{V}{m}$     |      1 $(\frac{1}{k_e})$       | in fact $\frac{s^2}{m^2}$    |
| Current                    |          1 A           |       1 $\frac{m^2}{s}$        |                              |
| Resistance                 |       1 $\Omega$       |  $(\frac{1}{k_e})\frac{s}{m}$  |                              |
| Capacitance                |          1 F           |           1 $(k_e)m$           |                              |
| Inductance                 |          1 H           | $(\frac{1}{k_e})\frac{s^2}{m}$ |                              |
| Magnetic field H           |    1 $\frac{A}{m}$     |        1 $\frac{m}{s}$         |                              |


It can be noticed that most of the electric units somehow are related to the factor $k_e$. When used only in electrical conditions, this factor somehow is anhillated. This will be explained with some examples. The exception to this is the definition of the current.

> $\tau= R.C$
>
> $\tau = (\frac{1}{k_e})\frac{s}{m}.(k_e).m $
>
> $\tau = \frac{s}{m}.m = s$ 
>
> Which provide obviously the correct answer, but is independed of the factor containing the speed of light.

When looking further to the electrical units:
| description      |     SI-unit     |            ms-unit             | full unit                    |
| ---------------- | :-------------: | :----------------------------: | ---------------------------- |
| Voltage          |       1 V       |      1 $(\frac{1}{k_e})m$      | $1.11e^{-10}\frac{s^2}{m}$   |
| Electric Field E | 1 $\frac{V}{m}$ |      1 $(\frac{1}{k_e})$       | $1.11e^{-10}\frac{s^2}{m^2}$ |
| Current          |       1 A       |       1 $\frac{m^2}{s}$        | $1 \frac{m^2}{s}$            |
| Resistance       |   1 $\Omega$    |  $(\frac{1}{k_e})\frac{s}{m}$  | $1.11e^{-10}\frac{s^3}{m^3}$ |
| Capacitance      |       1 F       |           1 $(k_e)m$           | $8.98e^{9}\frac{m^3}{s^2}$   |
| Inductance       |       1 H       | $(\frac{1}{k_e})\frac{s^2}{m}$ | $1.11e^{-10}\frac{s^4}{m^3}$ |
| Magnetic field H | 1 $\frac{A}{m}$ |        1 $\frac{m}{s}$         | $1 \frac{m}{s}$              |

The units for capacitance and resistance make sense:

> $C=\varepsilon \frac{A}{d} \mapsto [m]$
>
> $R= \rho \frac{l}{A} \mapsto [\frac{s}{m}]​$ In this case $\rho \mapsto [s]​$ (a factor related to time?) 
>
> $Q=V.C \mapsto [m^2]$
>
> $P=U.I \mapsto [\frac{m^3}{s}]$  **this is not expected**, should be $[\frac {m^5}{s^3}]$ 



A solution to this could be a unit offset, for example multiplying all units with $k_e$ can solve this imbalance in units. 





Are there ambiguities in the definition of charges? Let start with Coulombs Law.
$$
F=k_e\frac{Q^2}{r^2} => \frac{m^2}{s^2}.\frac{m^4}{m^2} = \frac{m^4}{s^2}
$$
This gives the right units expressed in meter and seconds, charge $Q$ is expressed in $[m^2]$let us assume this is correct.
$$
I=\frac{Q}{t} => \frac{m^2}{s}
$$






























