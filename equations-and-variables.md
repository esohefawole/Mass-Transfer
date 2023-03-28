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

Fick's Law (binary mixture A and B):
- mole flux of species A: $\underline{J_A} = -D_{AB} \underline{\nabla} c_A = -c D_{AB} \underline{\nabla} x_A$  
- mass flux of species A: $\underline{j_A} = -D_{AB} \underline{\nabla} \rho_A = -\rho D_{AB} \underline{\nabla} m_A$  

$\cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot$  

### Mass transfer relative to fixed coordinates (moles)  

Absolute molar flux: $\underline{N_A''} = c_A \underline{v_A}$ or $\underline{N_B''} = c_B \underline{v_B}$  

Total molar flux: $\underline{N''} = c \underline{v}^* = \underline{N_A''} + \underline{N_B''}$   
where the molar-averaged velocity $\underline{v}^* = x_A \underline{v_A} + x_B \underline{v_B}$  

Molar flux relative to molar-averaged flux of species A:  
$\underline{J_A}^* = c_A (\underline{v_A}- \underline{v}^*)$  

Plugging in $\underline{N_A''}$ and $\underline{v}^*$ into $\underline{J_A}^*$ equation gives:  

$\underline{N_A''} = -D_{AB} \underline{\nabla} c_A + x_A(\underline{N_A''} + \underline{N_B''})$

$\cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot$  

### Mass transfer relative to fixed coordinates (mass)  

Absolute mass flux: $\underline{n_A''} = \rho_A \underline{v_A}$ or $\underline{n_B''} = \rho_B \underline{v_B}$  

Total mass flux: $\underline{n''} = \rho \underline{v} = \underline{n_A''} + \underline{n_B''}$   
where the mass-averaged velocity $\underline{v} = m_A \underline{v_A} + m_B \underline{v_B}$  

Molar flux relative to molar-averaged flux of species A:  
$\underline{j_A} = \rho_A (\underline{v_A}- \underline{v})$  

Plugging in $\underline{n_A''}$ and $\underline{v}$ into $\underline{j_A}^*$ equation gives:  

$\underline{n_A''} = -D_{AB} \underline{\nabla} \rho_A + m_A(\underline{n_A''} + \underline{n_B''})$

$\cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot$  

### Species Conservation Equations (for species i)

Molar: $\frac{\partial c_i}{\partial t} + \underline{\nabla} \cdot \underline{N_i''} - \dot{N_i} = 0$  
- $\frac{\partial c_i}{\partial t}$ is the accumulation in microscopic control volume
- $\underline{\nabla} \cdot \underline{N_i''}$ is the divergence of flux in microscopic control volume
- $\dot{N_i}$ is the molar rate of increase of species i in microscopic control volume due to reactions  

Mass: $\frac{\partial \rho_i}{\partial t} + \underline{\nabla} \cdot \underline{n_i''} - \dot{n_i} = 0$ (same term definitions as above but for mass)  

$\cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot$  

### Predicting $D_{AB}$ for Gases  

1. Completely emperical
    - $D_{AB} = \alpha + \beta T + \gamma T^2$
        - $\alpha, \beta, \gamma$ are regression coefficients specified at a particular pressure
2. Theoretical (Chapman and Enskog)
    - $D_{AB} = \frac{1.86 \times 10^{-3} T^{3/2} (\frac{1}{M_A} + \frac{1}{M_B})^{1/2}}{P \sigma_{AB}^2 \Omega}$
        - $\sigma_{AB} = \frac{1}{2} (\sigma_A + \sigma_B)$ where $\sigma_i$ is "hard sphere diameter

