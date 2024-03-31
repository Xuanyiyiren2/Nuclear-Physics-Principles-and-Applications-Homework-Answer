Name: 张轩
Student ID: 21300200034

## Question 1

A material is found to have a tenth-thickness of $2.3\,\mathrm{cm}$ for $1.25\,\mathrm{MeV}$ $\gamma$ rays, 

- (a) What is the linear attenuation coefficient for this material? 
- (b) What is the half-thickness? 
- (c) What is the mean-free-path length for 1.25 MeV photons in this material?

#### Answer

(a) the tenth thickness is $x_{1/10}=\frac{\ln 10}{\mu}$. Thus the linear attenuation coefficient is $\mu=\frac{\ln 10}{x_{1/10}}=1.001\,\mathrm{cm^{-1}}$.

(b) the half-thickness is $x_{1/2}=\frac{\ln 2}{\mu}=\frac{\ln 2}{\ln 10}\frac{\ln 10}{\mu}=\lg 2\cdot x_{1/10}=0.69\,\mathrm{cm}$.

(c) The mean-free-path is the same as the lifetime of a particle. The lifetime $\frac 1\lambda$ is the Reciprocal of the Poisson parameter $\lambda$. Thus the mean-free-path is just $\bar x=\frac 1\mu=\frac{x_{1/10}}{\ln 10}=1.00 \,\mathrm{cm}$.

## Question 2

The specific rate of energy loss $-\frac 1\rho\frac{\mathrm{d}E}{\mathrm{d}x}$ of a $5\,\mathrm{MeV}$ proton in silicon is $59\,\mathrm{keV\,mg^{-1}cm^2}$ and its range $R'$ is $50 \,\mathrm{mg\,cm^{-2}}$ . Calculate values of $-\frac 1\rho \frac{\mathrm{d}E}{\mathrm{d}x}$ and range $R'$ for deuterons, tritons, $\ce{^{3}He}$ and $\alpha$ particles, all of which have the same speed as the proton.

#### Answer

According to the Bethe-Bloch formula,
$$
\left(-\frac{\mathrm{d}E}{\mathrm{d}s}\right)_{\text {coll }}=\rho \frac{Z}{A} z^2 f(I, \beta)
$$
The collisional stopping power also depends on the density $\rho$ of the stopping medium, the ratio $Z/A$ of the medium's atomic number to the atomic mass (atomic mass units), and the effective ionization potential $I$ (typically a few tens of eV) of the medium.

Due to all the particles have the same speed, the $\rho \frac{Z}Af(I,\beta)$ is the same for every case. Only the $z^2$ for the incoming particles differ.

The range is the energy divided by the stopping power.
$$
R\propto E/\left(\frac 1\rho\frac{\mathrm{d}E}{\mathrm{d}x}\right)
$$


|         Particle         | Charge $z$ | Stopping Power($\mathrm{keV\,mg^{-1}cm^2}$) | Energy rate | Range($\mathrm{mg\,cm^{-2}}$) |
| :----------------------: | :--------: | :-----------------------------------------: | :---------: | :---------------------------: |
|        proton $p$        |    $1$     |                    $59$                     |     $1$     |             $50$              |
|       deuteron $d$       |    $1$     |                    $59$                     |    $1/2$    |             $25$              |
|       tritons $t$        |    $1$     |                    $59$                     |    $1/3$    |            $16.7$             |
|       $\ce{^3He}$        |    $2$     |               $59\times4=236$               |    $1/3$    |            $4.17$             |
| $\alpha$ ($\ce{^{4}He}$) |    $2$     |               $59\times4=236$               |    $1/4$    |            $3.13$             |

## Question 3

A pulse of $10^{18}$ $100\,\mathrm{keV}$ X-ray photons per $\mathrm{m^2}$ is directed at right angles on to a $t=5\,\mathrm{mm}$ thick slab of iron. Calculate the temperature increase of the slab. Density of iron $\rho= 7870\,\mathrm{kg\,m^{-3}}$ mass attenuation coefficient for $100\,\mathrm{keV}$ photons on iron $\frac{\mu}{\rho}= 0.04\,\mathrm{ m^2 kg^{-1}}$, specific heat capacity of iron $c= 10^6 \mathrm{J\,kg^{-1}\,K^{-1}}$.

#### Answer

The linear attenuation coefficient is $\mu=\frac{\mu}{\rho}\cdot \rho=314.8\,\mathrm{m^-1}$.

$P=10^{18}\,\mathrm{m^{-2}}$. The number of gamma per $\mathrm{m}^2$ absorbed is
$$
N_\gamma =P(1-\mathrm{e}^{-\mu t})=7.93\times 10^{17}\,\mathrm{m^{-2}}
$$
So the energy absorbed is $E=N_\gamma \cdot 100\,\mathrm{keV}=7.93\times 10^{19}\,\mathrm{keV/m^2}$.

The total heat capacity of $1\,\mathrm{m^2}$ slab is
$$
C=mc=\rho tc\cdot 1\,\mathrm{m^2}=3.94\times 10^7 \,\mathrm{J/K}
$$
Thus the temperature increase is
$$
T = E/C = 3.23\times 10^{-4}\,\mathrm{K}
$$

## Question 4

When a slab of material is inserted between a collimated $\ce{^60Co}$ source and a detector, it is found that the fluxes of $1.17$ and $1.33\,\mathrm{MeV}$ $\gamma$ rays are reduced, respectively, to $62$ and $65\%$ of their values with no absorber. Calculate the ratio of the attenuation coefficients of the material for the two energies. What would be the reduction in the fluxes if two slabs were used?

### Answer

The percentage of $\gamma$ ray left is $\mathrm{e}^{-\mu t}$, with $t$ as the thickness.
$$
\mathrm{e}^{-\mu_1 t}=0.62\\
\mathrm{e}^{-\mu_2 t}=0.65
$$
Thus we have
$$
\mu_1t= 0.48,\mu_2t=0.43
$$
One can get
$$
\frac{\mu_1}{\mu_2}=\frac{\mu_1t}{\mu_2t}=1.11
$$
If two slabs are used, the percentage of left $\gamma$ ray is
$$
r_1=\mathrm{e}^{-2\mu_1t}=38.4\%,r_2=\mathrm{e}^{-2\mu_2t}=42.3\%
$$
