---
title: Homework 1 Study Guide
weight: 15
---

## The Kinchin-Pease model for displacements

The Kinchin-Pease (K-P) model is a simplifed estimate of the number of displaced atoms ($N_d$) per PKA[^1] by means of the simple set of proposed relationships:

$N_d = \begin{cases}
  0 & \text{for }0< E<E_d\\\  
  1 & \text{for }E_d<E<2E_d\\\\
  \frac{E} {2E_d} &   \text{for }2E_d<E<E_i\\\\
  \frac{E_i} {2E_d} & \text{for }E_i<E\\\
\end{cases}$

Where $E$ is the energy of the PKA and $E_d$ is the threshold energy. As energies above $E_i$, the recoils lose energy only by electron excitation, while below $E_i$ the energy transfer and loss is controlled by hardsphere elastic interactions (e.g. scattering). Note, the simplified model does not account for the effects due to the crystal lattice (e.g. crystal strucutre effects) for either single interactions or more complex damage cascades.

{{% notice warning %}}
The K-P model is only valid assuming classical elastic collision of hard spheres. The concept of recombindation is not considered in the model!
{{% /notice %}}



{{%expand "**Example Problems**" %}}Test.{{% /expand%}}



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




[^1]: PKA: Primary knock-on atom