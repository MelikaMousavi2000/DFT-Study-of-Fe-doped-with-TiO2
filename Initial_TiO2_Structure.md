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

First, The initial crystal structure of anatase TiO₂ was obtained from the AFLOW crystallographic database and imported into BIOVIA Materials Studio 2024.
<img width="1920" height="1080" alt="Screenshot (2046)" src="https://github.com/user-attachments/assets/340a7758-9278-4e6d-af49-17e32792713c" />

The display style was changed to Ball and Stick to better visualize the atomic arrangement.
<img width="1920" height="1080" alt="Screenshot (2047)" src="https://github.com/user-attachments/assets/bf6fd03b-9c55-44a7-850a-a5e523f0ea2f" />

---

## 3. The Crystal Symmetry in Anatase TiO₂ 
Symmetry means that a structure remains unchanged after a specific operation, such as rotation, reflection or translation. In anatase TiO₂, titanium (Ti) and oxygen (O) atoms are arranged in a regular and repeating pattern. Crystal symmetry helps us understand how this atomic arrangement repeats and which operations leave the structure unchanged.

<img width="1920" height="1080" alt="symmery" src="https://github.com/user-attachments/assets/ac2be1e8-7532-4cec-9ac5-aee0aa01607a" />

### 1️⃣ Periodicity: 3D (Crystal)
The unit cell shown in Materials Studio represents a small repeating part of the crystal. By repeating this unit cell along the three lattice vectors (a, b, and c), a larger crystal can be constructed.

<img width="1312" height="1199" alt="Repeating Anatase TiO₂ Crystal Lattice" src="https://github.com/user-attachments/assets/6745e635-0389-4140-8760-975e93f4583e" />

### 2️⃣ Crystal System: Tetragonal
Anatase TiO₂ belongs to the tetragonal crystal system and for a conventional tetragonal unit cell:

a = b ≠ c

α = β = γ = 90°

<img width="1448" height="1086" alt="Anatase TiO₂ Tetragonal Unit Cell" src="https://github.com/user-attachments/assets/6afe40c2-7590-493e-9d75-5ec2ccd7641b" />

### 3️⃣ Space Group: I4₁/amd
A space group tells us which symmetry operations can be applied to atoms or groups of atoms to generate equivalent positions in a crystal. Each letter and number represents a specific symmetry element or lattice-centering characteristic of the crystal.

The letter I (From the word Innenzentriert) indicates a body-centered lattice, meaning that in addition to the lattice points at the corners of the unit cell, there is an equivalent lattice point at its center.

<img width="585" height="341" alt="images" src="https://github.com/user-attachments/assets/34b13603-e039-4b73-a466-c0ec93be518e" />

### 4️⃣ International Tables Number: 141
In crystallography, there are 230 different three-dimensional space groups and each space group has a unique identification number. For anatase TiO₂, the space group is I4₁/amd, and its international number is 141.

### 5️⃣ Origin Choice: Origin-2
The starting point is called the origin. In crystallography, atomic positions are described relative to a chosen origin. Origin-2  means that the second standard origin convention is being used for the selected space group.

### 6️⃣ Crystal Class: 4/mmm

4: Fourfold rotational symmetry
m: Mirror symmetry
4/mmm: A tetragonal point group containing rotational and mirror symmetries

### 7️⃣ Long Name: I 4₁/a 2/m 2/d

I: Body-centered lattice

4₁: Fourfold screw axis

a: Glide plane involving a translation along the a direction

2: Twofold rotational symmetry

m: Mirror plane

d: Diamond-glide plane

### 8️⃣ Schoenflies Name: D₄h¹⁹
The symbol D₄h describes the point-group symmetry, while the superscript 19 identifies the corresponding space group within this Schoenflies family.

### 9️⃣ Body-Centered Lattice Translations
In anatase TiO₂, shifting the entire atomic arrangement by (½, ½, ½) of the conventional lattice vectors produces an equivalent crystal arrangement. This additional translational symmetry explains why the conventional cell contains 12 atoms (4 Ti + 8 O), while the smaller primitive cell contains only 6 atoms (2 Ti + 4 O). Both represent the same crystal structure.

### 🔟 Number of Symmetry Operators: 32
Anatase TiO₂ has 32 symmetry operations associated with its space group I4₁/amd, including rotations, reflections, and combinations with translations. These operations allow us to identify equivalent atomic positions without defining every atom independently.

---

## Verification of Lattice Parameters of Anatase TiO₂
The lattice parameters of the imported anatase TiO₂ structure were examined in BIOVIA Materials Studio using the Rebuild Crystal → Lattice Parameters window.

<img width="1419" height="722" alt="Screenshot (2061)" src="https://github.com/user-attachments/assets/c16bc7ea-3e31-4759-a906-c700340c4960" />

The results satisfy the geometrical conditions of a conventional tetragonal unit cell:

a = b ≠ c

α = β = γ = 90°

The equal values of a and b describe a square basal plane, while c represents the longer third lattice direction.
These values are consistent with the expected conventional-cell geometry of anatase TiO₂ and will be used as reference values when evaluating the geometry-optimized structure.

---

## 🔬 Atomic Composition Verification
Counting Ti and O atoms helps verify the correct Ti:O = 1:2 ratio in anatase TiO₂ and ensures that our initial crystal structure is suitable for DFT calculations. It also helps us compare our model with published studies, select an appropriate supercell, and determine the Fe doping concentration for future calculations.

<img width="1920" height="1080" alt="Screenshot (2062)" src="https://github.com/user-attachments/assets/1a49e66a-f9cb-45e2-add4-53e79e3bf63d" />

The conventional unit cell contains 4 Ti and 8 O atoms, corresponding to the correct stoichiometric ratio of Ti:O = 1:2. This confirms that the atomic composition is consistent with anatase TiO₂ and provides a suitable starting structure for subsequent DFT calculations.


## 3. Geometry Optimization Using CASTEP

After constructing the initial anatase TiO2 structure, geometry optimization was performed using the CASTEP module in Materials Studio.

The initial atomic positions do not necessarily represent the most stable configuration of the crystal. This is because atomic arrangements are influenced by:
1. electrostatic attraction between nuclei and electrons
2. nucleus–nucleus repulsion
3. electron–electron repulsion
4. chemical bonding interactions.

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

and also for the geometry optimization of pristine anatase TiO₂, Full Cell Optimization was selected in CASTEP. This option allows CASTEP to adjust both the atomic positions and the unit-cell parameters (a, b, and c) to find a more energetically stable structure. The goal is to obtain optimized lattice parameters and compare them with the initial values and published reference data.

<img width="1920" height="1080" alt="Screenshot (2071)" src="https://github.com/user-attachments/assets/91ce0e8b-b630-42a6-9312-766fd41ea456" />

### Geometry Optimization Algorithm Settings

<img width="1920" height="1080" alt="Screenshot (2072)" src="https://github.com/user-attachments/assets/77301eee-6bc1-4d8f-9632-b4a278cd8edc" />

### Geometry Optimization Algorithm Settings

**Algorithm: LBFGS**

The LBFGS algorithm was selected to help CASTEP find a lower-energy structure. It uses the calculated atomic forces and information from previous steps to determine how the atoms and lattice parameters should change during optimization.

**Use Line Search: Enabled**

Line Search was enabled to help CASTEP choose an appropriate step size. This prevents unnecessarily large movements and helps the optimization proceed more smoothly toward a stable structure.

**Use Delocalized Internals: Disabled**

This option was disabled because our anatase TiO₂ structure can be optimized using the standard atomic coordinate representation. Delocalized internal coordinates provide an alternative way to describe structural changes using combinations of bond lengths and angles, but they are not necessary for our initial optimization.

**Damped MD: Inactive**

Damped Molecular Dynamics is another method for optimizing structures by gradually reducing simulated atomic motion. Since we selected LBFGS as our optimization algorithm, Damped MD was not used.

