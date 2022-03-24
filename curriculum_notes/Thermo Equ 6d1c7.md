# Thermo Equations & Concepts Sheet

**Table of Contents**

## Convention

---

**Work**

- **Positive** = "By the system", internal energy decreases
- **Negative** = "On the system", internal energy increases

**Heat**

- **Positive** = "In" $\Rightarrow$  internal energy increases
- Negative = "Out" $\Rightarrow$  internal energy decreases

**Differentials**

- $d \Rightarrow \text{state function, single variable e.g. U(T)}$
- $\delta \Rightarrow \text{path function, e.g. q and w}$
- $\partial \Rightarrow \text{state function, multiple variable e.g.}\; P(V,T)$

**Macro Change**

- $\Delta \Rightarrow \int d \:\text{ or }\: \int\partial$

## First Law

---

<aside>
1️⃣                         $dU = \delta Q + \delta W$

</aside>

- Provides no restrictions on the direction of transfer

## Second Law

---

<aside>
🔥 **The Kelvin–Planck statement (Heat engines):** It is impossible to construct a device that will operate in a cycle and produce no effect other than the raising of a weight and the exchange of heat with a single reservoir.

</aside>

<aside>
🧊 **The Clausius statement (Refrigerator):** It is impossible to construct a device that operates in a cycle and produces no effect other than the transfer of heat from a cooler body to a warmer body.

</aside>

<aside>
😵‍💫 **Entropy View:** In any cyclic process the entropy will either increase or remain the same. See [**Entropy**](https://www.notion.so/Thermo-Equations-Concepts-Sheet-6683a7177c30428f9f922ea9e5b85c94)

$\Delta S_{tot} = \Delta S_{sys} + \Delta S_{surr}  \geq 0$

</aside>

- Acknowledges that processes proceed in a certain direction, but not in the opposite direction
- A cycle will occur only if both the first and second laws of thermodynamics are satisfies

### Statements on The Second Law of Thermodynamics

**Statement 1**

→ Limits the amount of heat

→ Available to do work

→ Thus constraining heat engine cycles

→ More tightly than did the first law

**Statement 2**

→ Restricts the direction of heat transfer

→ Precludes a perfect heat engine

→ Or a perfect refrigerator

→ And establishes the optimum efficiency in the Carnot Cycle

**Statement 3**

→ Can be stated in terms of entropy

→ Which establishes time's arrow

→ And is called the thermal bottleneck

## Enthalpy

---

<aside>
1️⃣             $H = U + PV$

</aside>

<aside>
2️⃣            $Q = \Delta U + P \Delta V \text{ since in this case }\:Q=\Delta H$

</aside>

Enthalpy is a state function by its definition. Enthalpy is de ned as $h = u + pv$, and because it is entirely comprised of state functions it must also be too. Sometimes people get tripped up on this question because $q = \Delta h$ for constant pressure processes, and q is a path function. The key to reconciling the ideas is in that $q = \Delta h$ when a particular path is defined (constant pressure), not all the time.

- Application of first law for a constant pressure system (isobaric)

## Entropy

---

<aside>
💫   $\text{Clausius inequality:  }\:\:\partial S \geq \dfrac{\delta Q}{T}$

</aside>

Where q represents the energy transferred as heat by any type of process, with the equality being true for a reversible process. A broken down version of this equation is: 

<aside>
🔨        $\partial S = \dfrac{\delta Q_{rev}}{T} \:\text{ and }\: \partial S > \dfrac{\delta Q_{irrev}}{T}$

</aside>

<aside>
🔁         $dS = \dfrac{\delta Q}{T} + \delta S_{gen} \:\:\text{ provided that }\:\:\delta S_{gen} \geq 0$

</aside>

The amount of entropy, $\delta S_{gen}$ , is the entropy generation in the process due irreversibilities occurring inside the system. 

**Visual Definition**

It's a measure of how spread out your energy is [**[Steven Mould YouTube]**](https://youtu.be/w2iTCm0xpDc)

- Energy is only useful when it is clumped together
- Energy is always spreading out

**Other Definitions of Entropy**

1. A state variable who change is defined for a reversible process at T where Q is the heat absorbed
2. A measure of the amount of energy that is unavailable to do work
3. A measure of the disorder of a system
4. A measure of the multiplicity of a system

## Gibbs Free Energy

---

<aside>
🆓                    $\Delta G = \Delta H - T\Delta S$

</aside>

Under conditions of constant pressure the Gibbs energy will predict the natural direction of any process

The Gibbs Free Energy expression that from the perspective of the system, there are two driving "forces" towards spontaneity, a decrease in energy (exothermic reactions contribute to negative $\Delta G$) and an increase in entropy (T is always positive, so only a [+] $\Delta S$  would contribute to a negative $\Delta G$ via the [$-T\Delta S$] term.)

| Type | ⁍ | ⁍ | ⁍ |
| --- | --- | --- | --- |
| 1 | [+] | [-] | Always [+], never spontaneous |
| 2 | [-] | [-] | [-] at low T, enthalpy driven process only spontaneous at low T |
| 3 | [+] | [+] | [-] at high T, entropy driven process only spontaneous at high T |
| 4 | [-] | [+] | Always [-], spontaneous at all T, both enthalpy and entropy driven |

## Hess's Law

---

<aside>
📌 $\Delta_{rxn}h \degree = \displaystyle\sum_{products} \nu \Delta_f h\degree - \displaystyle\sum_{reactants} \nu \Delta_f h\degree$

where $\nu$ are the stoichiometric coefficients for the reaction

</aside>

## Heat Capacity

---

$c_v = (\frac{\partial U}{\partial T})_v$

$c_p = (\frac{\partial H}{\partial T})_p$

$q = c_v\Delta T$

$\text{For an ideal gas}\:c_v = \frac{3}{2}R$

## Work

---

$\delta W = -Fdl$

$W = -P_{ex} (V_f - V_i)$

$W  = -nRT\;\ln(\frac{V_f}{V_i})$

## Processes

---

![pvdiagram.jpeg](Thermo%20Equ%206d1c7/pvdiagram.jpeg)

- Every point on a PV diagram represents a different state for the gas (given a pressure and volume)
- The are under the curve is *work*
- Not represented in the diagram is the *temperature* for the given state
- The change in internal energy ($\Delta U$) is not defined by the path and will be the same for any two given states
    - In contrast, **work** and **heat** are dependent on the path taken

### Isobaric $\Delta P = 0, \:\text{Constant pressure}$

$W = P\Delta V$

→ $W = nR \Delta T$

$Q = nc_p \Delta T$

$\Delta U = Q + P\Delta V$

→ $\Delta U = nc_v \Delta T$

### Isothermal $\Delta T = 0,\:\text{Constant temperature}$

$\Delta (PV) = 0$ 

$W = nRT\;\ln[\frac{V_f}{V_i}]$

$Q =nRT\;\ln[\frac{P_i}{P_f}]$

$U \propto T \; \therefore \; \Delta U = 0$

- $0 = Q + W$
- The process is slow that heat can always have time to flow in or out so there is no temperature change

$\text{Boyles Law: } P_1V_1 = P_2 V_2$

### Isochoric $\Delta V = 0,\;\text{Constant volume}$

→ (Also called Isometric or Isovolumetric)

$W = 0\;\therefore\;\Delta U = Q$

- No area under the curve, no work done

$Q = nc_v \Delta T$

$\text{Charles Law: } \frac{P_1}{T_1} = \frac{P_2}{T_2}$

### Adiabatic $Q = 0,\;\text{No heat exchanged}$

→ Does not mean there is no temperature change

$\therefore \Delta U = -W$

No thermal energy conducted or taken from the system

Steeper as we want the process to happen quickly so that there is no chance for heat to be exchanged

$W = -nc_v \Delta T$

## Energy

---

<aside>
⚡                      $<E> \;=\; k_BT\dfrac{\partial \ln (Z)}{\partial T}$

</aside>

## Efficiency

---

<aside>
💯                   $\epsilon = \dfrac{W_{out}}{Q_{in}}$      $0 < \epsilon < 1$

</aside>

$\epsilon = \eta = \dfrac{W_{net}}{q_{in}}$

## Ideal Gas Law

---

Assumptions:

- 

<aside>
⛽                         $PV = nRT$

</aside>

- For a closed system ($n$  is constant) we can state that:
    
    $PV \propto T  \;\therefore \;U \propto T \propto PV$
    

$\text{Ideal gas constant: }R = 8.3145 \text{J/mol-K}$

- $R = k \;\cdot\; N_A$
- $k = \text{Boltzmann constant} = 1.38066 \times 10^{-23}\:\text{J/K}$
- $N_A = \text{Avogadro's number} = 6.0221 \times 10^{23} \text{/mol}$

$\text{For an ideal monoatomic gas}\:c_v = \frac{3}{2}R$

- $$$c_p = \frac{5}{2}R$

<aside>
☁️                 $\text{Boyle's law: }\;\; P_1V_1 = P_2V_2$

</aside>

- **Assumption**: Mass and temperature are constant
- Can be stated as pressure is inversely proportional to the volume: $P \propto \frac{1}{V}$

## Real Gases

Van der Waals Equation (or Van der Waals equation of state):  An equation of state that generalizes the ideal gas law based on plausible reasons that real gases do not act ideally. The 'b' term accounts for the molecular volume a real gas takes up. The 'a' term accounts for the fact that gas molecules do interact with each either with attractive or repulsive forces. 

<aside>
🗻 $\bigg( P + a \dfrac{n^2}{V^2}\bigg) (V - nb) = nRT$

</aside>

Where the SI units for the coefficients are $a = \dfrac{atm * L^2}{mol^2}$ (liters, not Length) and $b = \dfrac{L}{mol}$

## Engines & Energy Sources

**Daniel Cell**

![Untitled](Thermo%20Equ%206d1c7/Untitled.png)

Form of this is a gravity cell

**Solar Panels**

$E = 13.6 \;eV \;Z^2 [\frac{1}{n^2}]$ ← Energy of ionization equation

Z = 14, n^2 = 14, 13.6 eV = 1 Ry (Rydberg constant)

## Terminology & Colloquial Definitions

---

**Reversible process:** A process whose direction can be reversed to return the system to its original state by inducing infinitesimal change to some property of the system's surroundings

- Reversibility means the reaction operates continuously at quasi-equilibrium
- A reversible transformation will take place when a system moves by infinitesimal amounts, and infinitesimally slowly, between equilibrium states such that the direction of the process can be reversed at any time
- In a reversible process, the entropy of the universe (i.e., the system plus surroundings) remains constant
- Reversible processes represent the maximum amount of work that you can get out of a process

**Irreversibility**: 

- Processes include: friction, unrestrained expansion(expansion of a gas into a vacuum), heat conduction in the presence of a temperature gradient (surface heating/cooling), chemical reactions, turbulent mixing, and molecular diffusion, freezing of supercooled water, precipitation formation, mixing, deliquescence

**Quasi-equilibrium process (or quasi-static process):** A thermodynamic process that happens slowly enough for a system to remain in internal thermodynamic equilibrium  

**U [Internal energy]:** Count all the energy

**H [Enthalpy]:** How does U respond to Q in and out

**S [Entropy]:** Describes the relative probability

**G [Gibbs free energy]:** The balance between H & S

## Appendix

[Useful Resources](https://www.notion.so/ecce76769b444aa8ad2a99fc52ac2080)