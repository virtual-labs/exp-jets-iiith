### What is Measured?

During the experiment, the following quantities are measured:

- Diameter of the nozzle,
- Plan area of the collecting tank,
- Rise of water level in the collecting tank,
- Time required for collection,
- Balancing mass placed on the loading pan,
- Shape of the target surface (flat plate or hemispherical cup).

These measurements are used to determine the discharge, jet velocity, theoretical impact force, experimental force, and percentage error.

### Why are these Measurements Important?

#### Nozzle Diameter

The nozzle diameter determines the cross-sectional area of the jet and is required for calculating the jet velocity.

#### Rise of Water Level and Collection Time

These measurements are used to determine the discharge through the nozzle by the volumetric method.

#### Balancing Mass

The balancing mass provides the experimental force developed by the jet.

#### Shape of Target Surface

The force exerted by the jet depends upon the change in momentum of water. A hemispherical cup produces a larger force than a flat plate because it changes the direction of flow more significantly.

#### Comparison of Forces

Comparing the theoretical force obtained from the momentum equation with the experimentally measured force verifies the momentum principle.

### Sequential Calculations

#### Step 1

Calculate the nozzle area.

$$
A=\frac{\pi d^2}{4}
$$

where

- $d$ = nozzle diameter.

#### Step 2

Determine the discharge using the volumetric method.

$$
Q=\frac{A_t h}{t}
$$

where

- $A_t$ = plan area of collecting tank,
- $h$ = rise of water level,
- $t$ = collection time.

#### Step 3

Calculate the jet velocity.

$$
V=\frac{Q}{A}
$$

#### Step 4

Calculate the theoretical force.

For a flat plate,

$$
F_t=\rho QV
$$

For a hemispherical cup,

$$
F_t=2\rho QV
$$

where

$$
\rho=1000\ kg/m^3
$$

for water.

#### Step 5

Calculate the experimental force.

$$
F_e=mg
$$

where

- $m$ = balancing mass,
- $g=9.81\ m/s^2$.

#### Step 6

Calculate the percentage error.

$$
\%\ Error=\frac{|F_t-F_e|}{F_t}\times100
$$

### Solved Numerical Example

Given,

Nozzle diameter,

$$
d=0.01\ m
$$

Plan area of collecting tank,

$$
A_t=0.12\ m^2
$$

Rise of water level,

$$
h=0.05\ m
$$

Collection time,

$$
t=20\ s
$$

Balancing mass,

$$
m=0.12\ kg
$$

Nozzle area,

$$
A=\frac{\pi(0.01)^2}{4}
=7.85\times10^{-5}\ m^2
$$

Discharge,

$$
Q=\frac{0.12\times0.05}{20}
=3.0\times10^{-4}\ m^3/s
$$

Jet velocity,

$$
V=\frac{3.0\times10^{-4}}
{7.85\times10^{-5}}
=3.82\ m/s
$$

For a flat plate,

Theoretical force,

$$
F_t=1000\times3.0\times10^{-4}\times3.82
=1.15\ N
$$

Experimental force,

$$
F_e=0.12\times9.81
=1.18\ N
$$

Percentage error,

$$
\%\ Error=
\frac{|1.15-1.18|}{1.15}\times100
=2.61\%
$$

### Observation Table

#### Flat Plate

| Trial | Rise of Water Level (m) | Time (s) | Discharge ($10^{-4}\ m^3/s$) | Jet Velocity (m/s) | Experimental Force (N) | Theoretical Force (N) | Error (%) |
| :---: | ----------------------: | -------: | ---------------------------: | -----------------: | ---------------------: | --------------------: | --------: |
|   1   |                   0.050 |       20 |                         3.00 |               3.82 |                   1.18 |                  1.15 |      2.61 |
|   2   |                   0.060 |       20 |                         3.60 |               4.58 |                   1.67 |                  1.65 |      1.21 |
|   3   |                   0.070 |       20 |                         4.20 |               5.35 |                   2.26 |                  2.25 |      0.44 |
|   4   |                   0.080 |       20 |                         4.80 |               6.11 |                   2.94 |                  2.93 |      0.34 |

#### Hemispherical Cup

| Trial | Rise of Water Level (m) | Time (s) | Discharge ($10^{-4}\ m^3/s$) | Jet Velocity (m/s) | Experimental Force (N) | Theoretical Force (N) | Error (%) |
| :---: | ----------------------: | -------: | ---------------------------: | -----------------: | ---------------------: | --------------------: | --------: |
|   1   |                   0.050 |       20 |                         3.00 |               3.82 |                   2.31 |                  2.29 |      0.87 |
|   2   |                   0.060 |       20 |                         3.60 |               4.58 |                   3.30 |                  3.29 |      0.30 |
|   3   |                   0.070 |       20 |                         4.20 |               5.35 |                   4.51 |                  4.49 |      0.45 |
|   4   |                   0.080 |       20 |                         4.80 |               6.11 |                   5.88 |                  5.86 |      0.34 |

### Interpretation

The observations show that the force developed by the jet increases with increasing discharge and jet velocity because a larger flow rate produces a greater change in momentum.

For the same discharge, the hemispherical cup develops a larger force than the flat plate because the water undergoes a greater change in direction.

The experimental force obtained from the balancing weights closely agrees with the theoretical force predicted by the momentum equation, thereby verifying the principle of conservation of momentum for fluid flow.
