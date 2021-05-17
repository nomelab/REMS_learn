---
title: Homework 1 Study Guide
weight: 15
---

## The primary damage process

The interaction of energetic incident particles with atoms of an irradiated material lead to a dynamic process that includes local disturbances and reconstruction of lattice structure of the irradiated material. Given sufficient incident energy, these disturbances, typically in the form of atom displacements, outweighs the reconstruction, e.g. recombination, to form lattice defects that change the local and global properties of the material. Many times the community thinks of this response as negative, but in certain cases the changes can be beneficial, thus the term "radiation effects" is preferred over "radiation damage".

In order to understand radiation effects, we first need to evaluate the interaction of a single incident particle with a lattice atom. This is a simple two-body collision event where the collisions can lead to changes in the original direction of the incident particle, otherwise known as a scattering event. The collision can lead to three primary events with the atoms in the irradiated materials:

1. Creation of displacement damage, e.g. the production of lattice atoms that are shifted, or displaced, from their original lattice positions.
2. Changes in the local microchemistry by stopping of the bombarding particles or capture of particles in the atomic nucleus with consequent transmutation.
3. Electronic ionization of atoms - this process does not produce permanent damage in metal and metallic alloys.

We will spend the majority of the time discussing the first - displacement damage. In this process we are first interested in the energy transferred from the incident particle to lattice atom in the two-body collision. The energy of the process can be simply described by,

$$E_1=T_1+T_2+Q \label{eq:1}$$

where $E_1$ is the initial kinetic energy of the particle prior to the collision, $T_1$ and $T_2$ are the kinetic energies of the two particles and $Q$ is the inelastic energy loss. If we consider an elastic collision, where the internal state of the two particles remains unchanged or the total sum of kinetic energy remains constant, then the $Q$ term is dropped from the equation. 

In the simplest form, we assume a hard sphere (e.g. elastic) collision between the incident particle. A simple expression can be derived accounting for conservation of mass and energy. The expression in the center-of-mass coordinate system is then,

$$T=\frac{4M_1M_2}{( M_1+M_2 )^2}E \, sin^2 \theta/2$$

where $M_1$ and $M_2$ are the masses of the incident particle and the lattice atom at rest, respectively, E is the energy (typically given in eV) of the incident particle, and $\theta$ is the scattering angle. The maximum energy transfer, $T_m$, will occur during a head-on collision $(\theta = 180 ^{\circ})$ is,

$$T_m=\frac{4M_1M_2}{( M_1+M_2 )^2}E \,.$$

Thus, an elastic hard-sphere collision can have an energy transfer from 0 to $T_m$ where the energy spectrum depends on the type (mass, charge) and energy of the incident particles. The difference in this energy spectrum, as will be discussed in detail in later sections, leads to different damage development.

{{% notice warning %}}
The given equations for $T$ and $T_m$ are only valid for elastic hard-sphere collisions!
{{% /notice %}}

<details>
<summary><font size="5"><i class="fas fa-chevron-right"></i> Click for Example Problems</font></summary>

{{% notice tip %}}
### Example Problem #1

Calculate the velocity and energy for an Fe atom and a proton for an elastic head-on collision. The proton is accelerated to an initial energy of 1 MeV.
{{% /notice %}}
<br />

|Constant|Value|
|--------|-----|
|$M_{proton}$| $1.675\times10^{-27} \ kg$ -or- $1 \ Da$ |
|$E_{proton}$| 1 MeV |
|$M_{Fe}$| $55.845 \ Da$ |
| 1 $Da$ | $\frac{931.5 \ MeV}{c^2}$ |
| $c^2$ | $3\times10^8 \ m/s$ |



<span style="color:blue">*Solution*</span>

For a head-on collision, $\theta=\pi$ resulting in $sin^2 \theta/2 \rightarrow 1$ in, 

$$T=\frac{4M_1M_2}{( M_1+M_2 )^2}Esin^2 \theta/2$$

thus we can use:

$$T_m=\frac{4M_1M_2}{( M_1+M_2 )^2}E \ .$$

Plugging the values in the equation, we can find $T$ which in this case will also be the maximum energy transferred:

$$T_m=\frac{4\times1\times55.845}{( 1+55.845 )^2} 1 MeV =0.07 \ MeV\ .$$

Note, as long as we keep the mass units constant between the two particles (e.g. $Da$) we can input any unit into the calculation. 

To find the velocity, we know the kinetic energy ($E$ and $T$) can be related to the mass and velocity via,

$$E=\frac{1}{2}mv^2$$

and via conservation of energy then,

$$E_1=T_1+T_2$$

thus, the velocity of the Fe atom is given by,

$$v_{Fe}=\sqrt{\frac{2 T_2}{M_2}}$$

where,

$$v_{Fe}=\sqrt{\frac{2\times 0.07 MeV}{55.845 \times \frac{931.5}{(3\times 10^8)^2}}}=4.9\times10^5 \ m/s$$

Note, for mass given in Da we converted the mass to MeV using the expressions given in the above table.The velocity of the proton after collision is given by,

$$v_{proton}=\sqrt{\frac{2 (E_1-T_2)}{M_2}}$$

$$v_{proton}=\sqrt{\frac{2\times (1-0.07) MeV}{1 \times \frac{931.5}{(3\times 10^8)^2}}}=1.3\times10^7 \ m/s$$

</details>




## Concept of displacement energy

*To be added*

## The Kinchin-Pease model for displacements

The Kinchin-Pease (K-P) model[^1] is a simplified estimate of the number of displaced atoms ($N_d$) per PKA[^2] by means of the simple set of proposed relationships:

$N_d = \begin{cases}
  0 & \text{for }0< E<E_d\\\  
  1 & \text{for }E_d<E<2E_d\\\\
  \frac{E} {2E_d} &   \text{for }2E_d<E<E_i\\\\
  \frac{E_i} {2E_d} & \text{for }E_i<E\\\
\end{cases}$

Where $E$ is the energy of the PKA and $E_d$ is the threshold energy. As energies above $E_i$, the recoils lose energy only by electron excitation, while below $E_i$ the energy transfer and loss is controlled by hardsphere elastic interactions (e.g. scattering). Note, the simplified model does not account for the effects due to the crystal lattice (e.g. crystal structure effects) for either single interactions or more complex damage cascades.

{{% notice warning %}}
The K-P model is only valid assuming classical elastic collision of hard spheres. The concept of recombination is not considered in the model!
{{% /notice %}}


<details>
<summary><font size="5"><i class="fas fa-chevron-right"></i> Example Problems</font></summary>
To be Updated
</details>
<br />
<details>
<summary><font size="5"><i class="fas fa-chevron-right"></i> Test your knowledge</font></summary>

{{< quizdown >}}
## Test your knowledge
---
primary_color: blue
secondary_color: lightgray
text_color: black
shuffle_questions: false
---

## The charge of a neutron

---
shuffle_answers: false
---

Based on the K-P model, if an energetic particle has an energy less than $E_d$ then what happens to the struck atom?

> $E_d$ is the energy required to displace an atom

- [ ] The struck atom is displaced from the lattice site and is presumed to come to rest at a location in the lattice different from it's previous position
- [x] The struck atom is presumed to resume to it's lattice site after the interaction

{{< /quizdown >}}.

</details>

[^1]: [G.H. Kinchin and R.S. Pease, Rep. Prog. Phys. **18** 1, 1955](https://iopscience.iop.org/article/10.1088/0034-4885/18/1/301/)
[^2]: PKA: Primary knock-on atom