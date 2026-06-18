The objective of the Impact of Jet Experiment is to compare the theoretical force developed by a water jet with the experimentally measured balancing force.

During the experiment, the discharge through the nozzle and the balancing load are measured. These observations are used to calculate the jet velocity, theoretical impact force, experimental force, and percentage error.

### Measured Data

The following quantities are measured during the experiment.

|        Parameter        | Symbol | Unit  |
| :---------------------: | :----: | :---: |
|     Nozzle diameter     |  $d$   |   m   |
| Area of collecting tank | $A_t$  | m$^2$ |
|   Rise of water level   |  $h$   |   m   |
|     Collection time     |  $t$   |   s   |
|     Balancing mass      |  $m$   |  kg   |

For water,

$$
\rho=1000;kg/m^3
$$

and

$$
g=9.81;m/s^2
$$

### Calculation of Nozzle Area

The nozzle area is required to determine the velocity of the water jet.

The cross-sectional area of the nozzle is

$$
A=\frac{\pi d^2}{4}
$$

For

$$
d=0.01;m,
$$

$$
A=\frac{\pi(0.01)^2}{4}
$$

$$
A=7.85\times10^{-5};m^2
$$

### Calculation of Collected Volume

The volume of water collected in the tank is calculated from the tank area and the rise in water level.

$$
V_c=A_t h
$$

For

$$
A_t=0.12;m^2
$$

and

$$
h=0.05;m,
$$

$$
V_c=0.12\times0.05
$$

$$
V_c=0.006;m^3
$$

### Calculation of Discharge

The discharge represents the volume flow rate through the nozzle.

$$
Q=\frac{V_c}{t}
$$

For

$$
V_c=0.006;m^3
$$

and

$$
t=20;s,
$$

$$
Q=\frac{0.006}{20}
$$

$$
Q=3.0\times10^{-4};m^3/s
$$

### Calculation of Jet Velocity

The velocity of the jet is obtained from the discharge and the nozzle area.

$$
V=\frac{Q}{A}
$$

Using

$$
Q=3.0\times10^{-4};m^3/s
$$

and

$$
A=7.85\times10^{-5};m^2,
$$

$$
V=\frac{3.0\times10^{-4}}{7.85\times10^{-5}}
$$

$$
V=3.82;m/s
$$

### Calculation of Theoretical Impact Force

The theoretical force depends upon the shape of the target.

#### Flat Plate

$$
F_t=\rho QV
$$

Substituting,

$$
F_t=1000\times3.0\times10^{-4}\times3.82
$$

$$
F_t=1.15;N
$$

#### Hemispherical Cup

$$
F_t=2\rho QV
$$

$$
F_t=2\times1000\times3.0\times10^{-4}\times3.82
$$

$$
F_t=2.29;N
$$

### Calculation of Experimental Force

The balancing weights applied to the loading pan produce the experimental force.

$$
F_e=mg
$$

For

$$
m=0.12;kg,
$$

$$
F_e=0.12\times9.81
$$

$$
F_e=1.18;N
$$

### Calculation of Percentage Error

The percentage error indicates the difference between the theoretical force predicted by the momentum equation and the experimentally measured balancing force.

The percentage error is calculated as

$$
%;Error=\frac{|F_t-F_e|}{F_t}\times100
$$

where,

- $F_t$ = theoretical force,
- $F_e$ = experimental force.

For the flat plate,

$$
F_t=1.15;N
$$

and

$$
F_e=1.18;N.
$$

Therefore,

$$
%;Error=\frac{|1.15-1.18|}{1.15}\times100
$$

$$
%;Error=\frac{0.03}{1.15}\times100
$$

$$
%;Error=2.61%
$$

A small percentage error indicates good agreement between the theoretical prediction based on the momentum equation and the experimentally measured force.

### Sample Calculation Summary

The calculations performed during the experiment follow the sequence

$$
A=\frac{\pi d^2}{4}
$$

$$
V_c=A_t h
$$

$$
Q=\frac{V_c}{t}
$$

$$
V=\frac{Q}{A}
$$

For a flat plate,

$$
F_t=\rho QV
$$

For a hemispherical cup,

$$
F_t=2\rho QV
$$

Experimental force,

$$
F_e=mg
$$

Percentage error,

$$
%;Error=\frac{|F_t-F_e|}{F_t}\times100
$$

### Sample Observation Table

| Trial | $h$ (m) | $t$ (s) | $Q$ ($10^{-4}$ m$^3$/s) | $V$ (m/s) | Mass (kg) | $F_e$ (N) | $F_t$ (N) | Error (%) |
| :---: | :-----: | :-----: | :---------------------: | :-------: | :-------: | :-------: | :-------: | :-------: |
|   1   |  0.050  |   20    |          3.00           |   3.82    |   0.12    |   1.18    |   1.15    |   2.61    |
|   2   |  0.060  |   20    |          3.60           |   4.58    |   0.17    |   1.67    |   1.65    |   1.21    |
|   3   |  0.070  |   20    |          4.20           |   5.35    |   0.23    |   2.26    |   2.25    |   0.44    |
|   4   |  0.080  |   20    |          4.80           |   6.11    |   0.30    |   2.94    |   2.93    |   0.34    |

### Interpretation

The theoretical force increases with the discharge and velocity of the jet because a larger flow rate produces a greater change in momentum. The experimental force obtained from the balancing weights should closely match the theoretical value, thereby verifying the momentum equation for the impact of a jet.
