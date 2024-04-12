Name: 张轩
Student ID: 21300200034

## Question 1

$\ce{^36Cl}$ decays into $\ce{^{36}S}(35.967081\,\mathrm{u})$ and ${ }^{36} \mathrm{Ar}$. If the energy release is $1.142\,\mathrm{MeV}$ to $^{36}\ce{S}$ and $0.709\,\mathrm{MeV}$ to $\ce{^{36}Ar}$, calculate the masses of $\ce{^{36}Cl}$ and $\ce{^{36}Ar}$. Describe the modes of decay.

#### Answer

The proton number of $\ce{^{36}Cl}$ and $\ce{^{36}S}$ is $17$ and $16$ thus
$$
\ce{^{36}Cl -> ^{36}S + e+}
$$
According to the conservation of energy, $Q_1=1.142\,\mathrm{MeV}= 0.001226\,\mathrm{u}$
$$
m_{\ce{^{36}Cl}} = m_{\ce{^{36}S}}+Q_1+m_{\ce{e}}\\
\Rightarrow m_{\ce{^{36}Cl}}= 35.968856\,\mathrm{u}
$$
For the second reaction, the proton number of $\ce{^{36}Ar}$ is $18$
$$
\ce{^{36}Cl ->^{36}Ar + e-}
$$
By the same way, we have $Q_2=0.709\,\mathrm{MeV}=0.000761\,\mathrm{u}$
$$
m_{\ce{^{36}Cl}} = m_{\ce{^{36}Ar}}+Q_2+m_{\ce{e}}\\
m_{\ce{^{36}Ar}} = m_{\ce{^{36}Cl}}-Q_2-m_{\ce{e}}=35.967546\,\mathrm{u}
$$
Both the mode of reaction is $\beta$-decay.

## Question 2

An initial number $N_{\ce{A}}(0)$ of nuclei $\ce{A}$ decay into daughter nuclei $\ce{B}$, which are also radioactive. The respective decay probabilities are $\lambda_\ce{A}$ and $\lambda_\ce{B}$. If $\lambda_\ce{B}=2\lambda_\ce{A}$ , calculate the time (in terms of $\lambda_\ce{A}$) when $N_\ce{B}$ is at its maximum. Calculate $N_\ce{B}$ (max) in terms of $N_\ce{A}(0)$.

#### Answer

The number of nuclei obey
$$
\begin{cases}
\dot N_\ce{A} &= -\lambda_\ce{A} N_\ce{A} \\
\dot N_\ce{B} &= \lambda_A N_\ce{A} - \lambda_B N_\ce{B}
\end{cases}
$$
Thus
$$
N_\ce{A}(t) = N_{\ce{A}0} \mathrm{e}^{-\lambda_\ce{A}t}\\
N_\ce{B}(t) =\lambda_A N_{\ce{A}0} \frac{\mathrm{e}^{-\lambda_Bt}-\mathrm{e}^{-\lambda_At}}{\lambda_A-\lambda_B}
$$
We can easily get the maximal point of $N_\ce{B}(t)$ ,
$$
\dot N_\ce{B}(t) = 0\\
\Rightarrow t_{\max}=\frac{\ln \lambda_\ce{A}-\ln \lambda_\ce{B}}{\lambda_A-\lambda_B}\\
N_{\ce{B}\max}=N_{\ce{A}0}\left(\frac{\lambda_\ce{A}}{\lambda_\ce{B}}\right)^{-\frac{\lambda_\ce{B}}{\lambda_\ce{A}-\lambda_\ce{B}}}.
$$
If $\lambda_\ce{B}=2\lambda_\ce{A}$, we have
$$
t_{\max} = \frac{2\ln2}{\lambda_\ce{A}}\\
N_{\ce{B}\max} = \frac{N_{\ce{A}0}}{2}
$$

## Question 3

The radionuclide $\ce{^{41}Ar}$ decays by $\beta$-emission to an excited level of $\ce{^{41}K}$ that is $1.293\,\mathrm{MeV}$ above the ground state. What is the maximum kinetic energy of the emitted $\beta$-particle?

#### Answer

$$
\ce{^{41}Ar -> ^{41}K^* + e-}
$$

The maximum kinetic energy of the emitted $\beta$-particle is all the released energy is given to $\ce{e-}$ but no $\bar\nu_e$.
$$
Q=m_{\ce{^{41}Ar}}-m_{\ce{^{41}K}} - 1.293\,\mathrm{MeV} - m_\ce{e-}=0.688\,\mathrm{MeV}
$$
Thus the kinetic of $\ce{e-}$ is
$$
T_\ce{e-} = Q \frac{m_{\ce{^{41}Ar}}}{m_{\ce{^{41}Ar}}+m_\ce{e-}}=0.688\,\mathrm{MeV}
$$

## Question 4

The activity of a radioisotope is found to decrease by $30\%$ in one week. What are the values of its 

- (a)decay constant
- (b) half-life
- (c) mean life?

### Answer

The law of radioactivity is the exponential distribution
$$
P(t\leq T)=1-\mathrm{e}^{-\lambda T}.
$$
If the radioisotope decrease by $30\%$ , this means
$$
P(t<T_1)=0.3,T_1=1\,\mathrm{wk} = 604800 \,\mathrm{s}
$$
Solving this equation we get
$$
\lambda = \frac{-\ln 0.7}{T_1}=5.897\times10^{-7}\,\mathrm{Bq}
$$
Now we can easily get the rest parameters,
$$
T_{1/2}=\frac{\ln 2}{\lambda} =\frac{\ln 2}{-\ln 0.7} T_1 =2350686\,\mathrm{s} = 1.943\,\mathrm{wk}\\
T_{\text{life}} = \frac{1}{\lambda } = \frac{T_1}{-\ln 0.7} = 3391323\,\mathrm{s} = 2.804\,\mathrm{wk}
$$
