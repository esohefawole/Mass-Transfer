# Mass Transfer Equations and Units

## Unit Symbol Definitions  
$m$: meters  
$g$: grams  
$s$: seconds   
$\theta$: theta (angle in radians)  
$mol$: moles  
$K$: Kelvin  
$J$: joules

## Variables with Units 

length(l), height (h), or width (w) [=] $m$  
diameter (d) or radius (r) [=] $m$  
area (A) [=] ${m^2}$  
volume (V) [=] $m^3$  
mass (m) [=] $g$  
velocity (v) [=] $\frac{m}{s}$  
temperature (T) [=] $K$  
gas constant (R) [=] $\frac{J}{K \cdot mol}$ 
pressure (P) [=] bar  
concentration (c) [=] $\frac{mol}{m^3}$  
density ($\rho$) [=] $\frac{kg}{m^3}$  
molecular weight (M) [=] $\frac{g}{mol}$  
molar flux ($\underline{J}$ or $\underline{N}$) [=] $\frac{mol}{m^2 \cdot s}$  
mass flux ($\underline{j}$ or $\underline{n}$) [=] $\frac{kg}{m^2 \cdot s}$  
diffusion coefficient (D) [=] $\frac{m^2}{s}$  
mass fraction for species i ($m_i$) [=] dimensionless  
mole fraction for species i ($x_i$) [=] dimensionless
hard sphere diameter ($\sigma$) [=] Angstroms  
chemical potential for species i ($\mu_i$) [=] $\frac{J}{mol}$  
Boltzmann constant ($k_b$) [=] $\frac{J}{K}$  
Henry's constant (H) [=] $bar$  
solubility (S) [=] $\frac{K \cdot mol}{m^3 \cdot bar}$  
shear stress ($\tau_s$) [=] $kg/{m \cdot s^2}$  

## Equations

### Definitions

For species i,
- $c_i = \frac{\rho_i}{M_i}$
- $x_i = \frac{c_i}{c}$
- $m_i = \frac{\rho_i}{\rho}$
- For ideal mixtures of ideal gases
    - $c_i = \frac{P_i}{R \cdot T}$
    - $\rho_i = \frac{P_i}{R_i \cdot T}$ where $R_i = \frac{R}{M_i}$

$\cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot$  
### Laws
Dalton's Law: $P = \sum P_i$  

Fick's Law:
- mole flux of species A: $\underline{J_A} = -D_{AB} \underline{\nabla} c_A = -c D_{AB} \underline{\nabla} x_A$  
- mass flux of species A: $\underline{j_A} = -D_{AB} \underline{\nabla} \rho_A = -\rho D_{AB} \underline{\nabla} m_A$