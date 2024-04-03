Name: 张轩
Student ID: 21300200034

All the calculation can be found in my repository on Github:

[https://github.com/Xuanyiyiren2/Nuclear-Physics-Principles-and-Applications-Homework-Answer/blob/main/hw2c/hw2c.ipynb](https://github.com/Xuanyiyiren2/Nuclear-Physics-Principles-and-Applications-Homework-Answer/blob/main/hw2c/hw2c.ipynb)

## Question 1

During a diagnostic $X$-ray, a broken leg with a mass of $5\,\mathrm{kg}$ receives an equivalent dose of $0.5\,\mathrm{mSv}$. If the $X$-ray energy is $50\,\mathrm{keV}$, how many X-ray photons were absorbed?

#### Answer

For $X$-ray the quality factor is $QF=1$, thus
$$
D = H/QF = 0.5 \,\mathrm{mGy}
$$
So the total energy is
$$
E = mD = 0.0025\,\mathrm{J}
$$
$\varepsilon = 50\,\mathrm{keV}$, the number of photons is
$$
N = E/\varepsilon = 3.12\times 10^{11}
$$

## Question 2

The entire body of a living subject weighing $5\,\mathrm{kg}$ has just received $1\,\mathrm{rad}$ of radiation. Express this dose in $\mathrm{SI}$ unit. Estimate the total energy deposited in it. Estimate the total number of ion pairs produced. 

#### Answer

The dose is
$$
D=1\,\mathrm{rad}=0.01\,\mathrm{Gy}=0.01\,\mathrm{J/kg}
$$
Total mass is $m=5\,\mathrm{kg}$. Therefore total energy is
$$
E = D\cdot m=0.05\,\mathrm{J}
$$
How much energy it takes to generate a pair of ions in human body in average?


## Question 3

If a radionuclide, with a physical half-life $t_{1/2}$, is ingested and has a biological half-life $t^b_{1/2}$, What is the effective half-life $t^e_{1/2}$, for the removal of the radioactive nuclide from the system?

#### Answer

The effective decay constant is the sum of the biological decay constant and physical decay constant.
$$
\lambda^e=\lambda+\lambda^b
$$
Thus using the relation $t_{1/2}^{i}=\frac{\ln 2}{\lambda^i}$, one can easily derive
$$
t^e_{1/2} = \frac{1}{\frac {1}{t_{1/2}}+\frac{1}{t^b_{1/2}}}.
$$

## Question 4

What is the gamma-ray absorbed dose rate ($\mathrm{Gy/h}$) in an infinite air medium at a distance of $10\,\mathrm{cm}$ from a $1\,\mathrm{mCi}$ point source of  

- (a) $\ce{^13N}$
- (b) $\ce{^43K}$

Decay data and energies can be found at this site:  [http://www.nndc.bnl.gov/mird/](http://www.nndc.bnl.gov/mird/)

### Answer

We will apply the formula
$$
\dot D(E)=\left(\frac{\mu_{en}(E)}{\rho}\right) E \phi
$$
We already know that $A = 1\,\mathrm{mCi},r = 10\,\mathrm{cm}$. We neglect the radiation lost in the $10\,\mathrm{cm}$ distance. So the flux density is
$$
\phi = \frac{S^o}{4\pi r^2}= 2.944\times 10^{5}\,\mathrm{s^{-1}cm^{-1}}
$$

#### $\ce{^13N}$

For $\ce{^13N}$, the only one energy of $\gamma$-decay is $E=0.5109\,\mathrm{MeV}$.

By Appendix C of our textbook, I created an interpolation curve of $\left(\frac{\mu_{en}}{\rho}\right)$ versus $E$. And I get
$$
\left(\frac{\mu_{en}}{\rho}\right)_{0.5109\,\mathrm{MeV}}=2.96576\times 10^{−2}\,\mathrm{cm^2/g}
$$
Thus 
$$
\dot D=\left(\frac{\mu_{en}}{\rho}\right) E \phi=1.423\times10^{-7}\,\mathrm{Gy/s} = 0.5120\,\mathrm{mGy/h}
$$

#### $\ce{^43K}$

All the calculation is the same as before, but this time we have $\gamma$-decay modes more then one. The formula is
$$
\dot D(E)=\phi\sum_{i}\left(\frac{\mu_{en}(E)}{\rho}\right)_i f_iE_i 
$$
By the help of `.csv` file on the website and the interpolate data in the Table C.3. We have

| Decay Mode | Energy(MeV) | Branching Ratio | mu_en/rho(cm2 / g) |
| :--------: | :---------: | :-------------: | :----------------: |
|     γ1     |   0.2206    |     0.2206      |     0.0272468      |
|     γ2     |   0.3727    |     0.3727      |     0.0293651      |
|     γ3     |   0.3968    |     0.3968      |     0.0294776      |
|     γ4     |   0.4042    |     0.4042      |     0.0295055      |
|     γ5     |   0.5933    |     0.5933      |     0.0295452      |
|     γ6     |   0.6174    |     0.6174      |     0.0294871      |
|     γ7     |    0.801    |      0.801      |     0.0288156      |
|     γ8     |   0.9902    |     0.9902      |     0.0279375      |
|     γ9     |    1.021    |      1.021      |     0.0277878      |
|    γ10     |    1.394    |      1.394      |     0.0259632      |

So the result is
$$
\dot D  = 1.33\times 10^{-7}\,\mathrm{Gy/s}=0.48\,\mathrm{mGy/h}
$$

## Question 5

Describe in your own words the rationale for the NCRP[1987] limit of $50 \,\mathrm{mSv}$ a year whole-body exposure for occupational workers. Give arguments why you do or do not believe this limit to be reasonable.

### Answer

In Section it is stated that the annual average occupational death rate is 100 per 1 million workers, i.e. $10^{-4}\,\mathrm{year^{-1}}$.

The average dose equivalent received by a radiation worker is, from page  257, $0.23\,\mathrm{rem}$.

The probability of a radiation-induced cancer is $10^{-4}$ per $\mathrm{rem}$. To set an limit on the annual dose a radiation worker can receive, we should keep the risk of dying from radiogenic cancer less or equals than the  accidental death rate accepted by non-radiation workers.

So

$$
\mathrm{Annual~dose~limit}\cdot \mathrm{risk~of~death/rem}=\mathrm{accidental~death~rate}=10^{-4}\,\mathrm{y}
$$
Thus
$$
\mathrm{Annual~dose~limit}=\frac{10^{-4} \mathrm{y}^{-1}}{0.23 \times 10^{-4} \mathrm{rem}^{-1}}=4.3 \mathrm{rem} / \mathrm{y} \simeq 50\,\mathrm{msV}
$$
