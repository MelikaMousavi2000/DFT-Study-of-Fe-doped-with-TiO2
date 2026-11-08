# Initial Anatase TiO2 Structure and Geometry Optimization

## 1. Electron Configuration of Titanium

The atomic number of titanium (Ti) is 22.

Its complete electron configuration is:

**Ti:**

1s² 2s² 2p⁶ 3s² 3p⁶ 4s² 3d²

The abbreviated electron configuration is:

**Ti: [Ar] 3d² 4s²**

Therefore, titanium has four valence electrons in its outermost electronic configuration (3d² 4s²).

### Oxidation State of Titanium in TiO2

In titanium dioxide (TiO2), titanium exhibits an oxidation state of +4.

The formation of the Ti4+ ion can be represented as:

Ti → Ti⁴⁺ + 4e⁻

During ion formation, the two 4s electrons are removed first, followed by the two 3d electrons.

The electron configuration of Ti4+ is:

**Ti4+: [Ar] 3d⁰**

The complete electron configuration becomes:

1s² 2s² 2p⁶ 3s² 3p⁶

Therefore, the Ti4+ ion has an empty 3d subshell.

### Oxidation State of Oxygen and TiO2 Stoichiometry

Oxygen commonly exhibits an oxidation state of −2 in metal oxides.

For an electrically neutral TiO2 formula unit, the sum of oxidation states must equal zero:

(+4) + 2(−2) = 0

Therefore, one titanium atom combines with two oxygen atoms to satisfy charge neutrality.

The resulting chemical formula is:

**TiO2**

The stoichiometric atomic ratio is:

**Ti : O = 1 : 2**

---

## 2. Construction of the Initial Anatase TiO2 Structure

First, the initial crystal structure of the anatase phase of titanium dioxide (TiO2) was constructed using BIOVIA Materials Studio.

The atomic composition was defined according to the stoichiometric ratio of titanium to oxygen (Ti : O = 1 : 2).

The initial unit cell contained:

- 2 Titanium (Ti) atoms
- 4 Oxygen (O) atoms

This composition corresponds to two TiO2 formula units and maintains the correct stoichiometric ratio.

---

## 3. Geometry Optimization Using CASTEP

After constructing the initial anatase TiO2 structure, geometry optimization was performed using the CASTEP module in Materials Studio.

The initial atomic positions do not necessarily represent the most stable configuration of the crystal. This is because atomic arrangements are influenced by electrostatic attraction between nuclei and electrons, nucleus–nucleus repulsion, electron–electron repulsion, and chemical bonding interactions.

Therefore, geometry optimization was performed to minimize the total energy, reduce residual atomic forces, and obtain a more stable atomic arrangement.

### 3.1. CASTEP Geometry Optimization Parameters

The following computational settings were selected:

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

### 3.2. Rationale for the Selected Parameters

**Geometry Optimization:** Selected to relax the atomic positions and obtain a more energetically favorable structure.

**Quality: Fine:** Selected to provide relatively high numerical accuracy for the calculation.

**GGA-PBE:** Selected as a widely used exchange-correlation functional for investigating the structural properties of crystalline materials.

**Non-polarized:** Selected for the initial pristine TiO2 structure, which was treated as a non-magnetic reference system.

**Metal: Disabled:** The pristine anatase TiO2 structure is a semiconductor rather than a metal.

**DFT+U: Disabled:** The initial calculation was performed using conventional GGA-PBE to establish a reference structural model. The effect of DFT+U will be evaluated in subsequent Fe-doped models.

**Spin-Orbit Coupling: Disabled:** SOC was neglected in the initial structural calculation to simplify the computational model.

**Total Charge: 0:** Selected to represent an electrically neutral TiO2 unit cell.

---

## 4. Objective of the Initial Calculation

The main objective of this stage was to construct and optimize a pristine anatase TiO2 reference structure.

This optimized structure will serve as the starting point for subsequent investigations of iron incorporation and its effects on the structural, electronic, magnetic, and surface properties of TiO2.

**Next Step:** Validation of the optimized structure and preparation of an appropriate supercell for Fe substitution.
