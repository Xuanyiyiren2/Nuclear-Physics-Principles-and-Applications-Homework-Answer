

## Question 1

A $\pu{50uCi}$ source emitting $\pu{5MeV}$ $\alpha$ particles is suspended between the plates of a large gas ionization chamber. If the emitted $\alpha$ particles lose all their energy in the chamber gas, calculate the current measured at the output. Assume that the average energy to create an ion pair in the gas is $\pu{34 eV}$ and that all the charges produced in the chamber are collected.

### Answer

The count rate of $\alpha$ particles is $n=\pu{50uCi}$ and every $\alpha$ particle can create $N=\frac{E}{I}$ ion pairs, in which $E$ is the energy of $\alpha$ particles and $I$ is the average ionization energy.
$$
N=\frac EI =\frac{\pu{5MeV}}{\pu{34eV}}=\pu{1.47E5}
$$
Thus the current is
$$
I = nN\cdot 1\mathrm{e}= \pu{4.36E-8 A}
$$
Here $\mathrm{e}=\pu{1.6021766E−19C}$ is electron charge.

## Question 2

Explain how a Geiger‑Muller counter works. What are its advantages and disadvantages for radiation measurement?

### Answer

The Geiger-Müller counter operates based on two principles: self-sustaining discharge and quenching.

1. **Self-sustaining discharge**: When ionizing particles pass through a gas-filled tube, they create ionization, leading to the production of more charged particles through a chain reaction. This self-sustaining discharge continues until certain factors halt the process.
2. **Quenching**: After each discharge, measures are taken to prevent the emission of secondary electrons from the cathode. This prevents further discharges and terminates the process.

The counter detects radiation by counting the number of discharges, providing information about the intensity of radiation or the energy of the particles.

The Geiger-Müller counter offers simplicity, sensitivity, and versatility, making it widely used for radiation measurement. However, it has limitations such as saturation at high radiation levels, inability to differentiate between types of radiation, and susceptibility to environmental factors like temperature and pressure.

## Question 3

The $\pu{4.4 MeV}$ $\gamma$ rays from the decay of the first excited state of  $\ce{^12C}$ to the ground state are observed using a $\ce{Nal}(\ce{Tl})$ scintillation detector. 

- (a) Explain how many peaks are observed instead of just one full-energy peak. What can you say regarding the relative heights of these peaks in relation to the size of the scintillation crystal? 
- (b) The pulse-height spectrum of a radioactive source, known to emit only monoenergetic $\gamma$ rays, shows three peaks at channel numbers 1650, 1252 and 854. What is the $\gamma$ ray energy?

### Answer

###### (a)

In fact, there are many peaks we can observe except the full-energy peak:

- The single escape peak, caused by one escaped electron in pair production.
- The double escape peak, caused by both two escaped electron in pair production.
- The backscatter peak, caused by some $\gamma$ scattered back from other materials.
- The annihilation radiation, caused by pair production happened outside the detector and the positive electron $e^+$ captured by our detector coincidently.

The full-energy peak is by no doubt the highest peak. Followed by the one single escape peak, and then the double escape peak. As for the backscatter peak and the annihilation, it depends on the detection environment.

###### (b)

If there were only there peaks for a monoenergetic $\gamma$ ray. The three peaks must be the full-energy peak, the single escape peak and the double escape peak. And the relation between energy $E$ and channel number $N$ is linear. Let's suppose the relation to be
$$
E/E_0 = AN+B,
$$
in which $E_0$ is the energy unit. We can set $E_0=\pu{1keV}$. 

Suppose the energy the $\gamma$-ray is $E_1$, then we have
$$
\begin{gather}
E_1/E_0=AN_1+B \label{eq:1}\\
(E_1-m_e)/E_0=AN_2+B \label{eq:2}\\
(E_1-2m_e)/E_0=AN_3+B \label{eq:3}
\end{gather}
$$
In which $N_1=1650,N_2=1252,N_3=854$ and the mass of electron is $m_e=\pu{511keV}$. Let use the equation$(\ref{eq:1})$ subtract the equation$(\ref{eq:2})$, we get
$$
m_e/E_0=A(N_1-N_2)\\
\Rightarrow A=\frac{m_e/E_0}{N_1-N_2}=1.284
$$
The result of subtracting $(\ref{eq:2})$ from $(\ref{eq:3})$ is exactly the same. So we cannot get what $E_1$ is without new information. It seems that the pulse-height spectrum has been zeroed, i.e., the zeroth channel corresponds to zero energy, which means $B=0$. Thus we can get solve $E_1$:
$$
E_1=E_0AN_1=\pu{2118keV}
$$
The energy of the $\gamma$ ray is $\pu{2118keV}$.

