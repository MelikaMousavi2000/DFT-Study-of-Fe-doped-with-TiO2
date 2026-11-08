Initial Anatase phase of TiO2 Structure and It's Geometry Optimization
Electron Configuration of Titanium: 
[
1s^2,2s^2,2p^6,3s^2,3p^6,4s^2,3d^2
]
So, It has four valence electrons in its outermost electronic configuration (3d² 4s²).
In titanium dioxide (TiO2), titanium exhibits an oxidation state of +4.
[
Ti\rightarrow Ti^{4+}+4e^-
]
During ion formation, the two 4s electrons are removed first, followed by the two 3d electrons.
The electron configuration of Ti4+ is:

[
Ti^{4+}=[Ar],3d^0
]

The complete configuration becomes:

[
1s^2,2s^2,2p^6,3s^2,3p^6
]

So, the Ti4+ ion has an empty 3d subshell.
Oxygen commonly exhibits an oxidation state of −2 in metal oxides.

For an electrically neutral TiO2 formula unit, the sum of oxidation states must equal zero:

[
(+4)+2(-2)=0
]

Therefore, one titanium atom combines with two oxygen atoms to satisfy charge neutrality.

The resulting stoichiometric composition is:

[
\boxed{TiO_2}
]

The atomic ratio is:

[
Ti=1:2
]
Step 1. Construction of the Initial Anatase TiO₂ Structure

First, the initial crystal structure of anatase titanium dioxide (TiO₂) was constructed using Materials Studio.

The atomic composition was defined according to the stoichiometric ratio of titanium to oxygen (Ti = 1:2). The initial unit cell contained:

2 Titanium (Ti) atoms

4 Oxygen (O) atoms

This composition ensures the correct stoichiometric ratio of TiO₂.

Geometry Optimization Using CASTEP

After constructing the initial structure, geometry optimization was performed using the CASTEP module in Materials Studio.
### CASTEP Geometry Optimization Parameters

| Parameter | Selected Setting |
|:---|:---|
| Task | Geometry Optimization |
| Quality | Fine |
| Exchange-Correlation Functional | GGA-PBE |
| Spin Polarization | Non-polarized |
| Metal | Disabled |
| DFT+U | Disabled |
| Spin-Orbit Coupling | Disabled |
| Total Charge | 0 |

The initial atomic positions do not necessarily represent the most stable configuration of the crystal. This is because the atoms are affected by electrostatic attraction between nuclei and electrons, repulsion between nuclei, electron–electron repulsion, and chemical bonding interactions.

So, geometry optimization was performed using CASTEP to minimize the total energy, reduce atomic forces, and obtain a more stable atomic arrangement.
