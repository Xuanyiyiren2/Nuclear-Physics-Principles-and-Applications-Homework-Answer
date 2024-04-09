## Question 1

What is the maximal energy that can be reached in a tandem Van de Graaff with a $15\,\mathrm{MV}$ field for the following ions (the negative ion state is given in brackets).

- $\ce{H+}(\ce{H−})$
- $\ce{C^2+}(\ce{C−})$
- $\ce{Au^3+}(\ce{Au−})$
- $\ce{U^10+}(\ce{U−})$

### Answer

The tandem Van de Graaff accelerator can generate beams with kinetic energy at $E_k=(1+q)eU$. 

We have $U=15\,\mathrm{MV}$

Thus

- $\ce{H+}(\ce{H−})$:$q=1,E_k=2\times15\,\mathrm{MeV}=30\,\mathrm{MeV}$
- $\ce{}$$\ce{C^2+}(\ce{C−})$:$q=2,E_k=45\,\mathrm{MeV}$
- $\ce{Au^3+}(\ce{Au−})$:$q=3,E_k=60\,\mathrm{MeV}$
- $\ce{U^10+}(\ce{U−})$:$q=10,E_k=165\,\mathrm{MeV}$



## Question 2

- a) What is the current produced by a Thermionic Tantalum cathode operating at $2700\,\mathrm{K}$ (assume no electric field)? 
- b) What is the current produced by a Cesium cathode operating at $500\,\mathrm{K}$? 
- c) How are these currents changed if the cathode is biased by a $100\,\mathrm{kV/cm}$ field?

### Answer

###### (a)

The work function of $\ce{Ta}$ is $W=4.1\,\mathrm{eV}$, so the current is
$$
J(2700\,\mathrm{K},\ce{Ta})=AT^2\exp\left(-\frac{W}{k_\mathrm{B}T}\right)=1.948\times 10^5\,\mathrm{A/m^2}
$$

###### (b)

The work function of $\ce{Ce}$ is $2\,\mathrm{eV}$, so the current is
$$
J(500\,\mathrm{K},\ce{Ce})=2.083\times 10^{-9}\,\mathrm{A/m^2}
$$

###### (c)

If a biased field is add, the Schottky emission should be considered.
$$
\Delta W=\sqrt{\frac{e^3 E}{4\pi\varepsilon_0}}=0.120\,\mathrm{eV}
$$
Thus
$$
J'(2700\,\mathrm{K},\ce{Ta})=AT^2\exp\left(-\frac{W-\Delta W}{k_\mathrm{B}T}\right)=3.262\times10^5\,\mathrm{A/m^2}\\
J'(500\,\mathrm{K},\ce{Ce})=3.374\,\mathrm{A/m^2}
$$

## Question 3

Give the name of 3 devices that allow beam size measurements and describe how they work. Make a quick comparison of Faraday cup and Beam current monitor.

### Answer

Three beam size measurements:

- Faraday Cup: 
  - Faraday cup uses a eletrometer to measure the total charge of the beams
- Beam current monitor:
  - By inserting a ceramic gap and an ammeter on the pipe, current induced by the beams on it can be measured.
- Screen:
  - Screens is made of scintillators. When particles hit the screen, they can deposit energy, which can caused emitted light from the scintillators. By using appropriate camera, we can measure the beam.

Faraday cup and Beam current monitor:

- A faraday cup destroys the beam, but it gives a very accurate charge measurements.
- A beam current monitor does not affect the beam but need to be calibrated.

## Question 4

What is the length $L$ of the longest drift tube in a linear accelerator of the Sloan-Lawrence type, which operates at a frequency f of $30\,\mathrm{MHz}$ and will accelerate $\ce{^16O}$ ions to $80\,\mathrm{MeV}$ ?

### Answer

Use the formula
$$
L=\frac{v}{2f}
$$
Considering the mass of $\ce{^16O}$ is $14899\,\mathrm{MeV}$, the speed of a $\ce{^16O}$ nuclei with kinetic energy at $80\,\mathrm{MeV}$ can be obtained without considering relativistic effects.
$$
v=\sqrt{\frac{2E_k}{m}}=3.11\times 10^7\,\mathrm{m/s}
$$
Thus $L=0.518\,\mathrm{m}$.