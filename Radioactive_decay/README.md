## Radioactive Decay 


This Python project simulates radioactive decay based on the user's input for the half-life, initial mass, and given time. 


## Overview
Certain atomic nuclei are unstable, and will over time decay into other nuclei, through emission of radiation. We call such atomic nuclei **radioactive**. The process of radioactive decay is completely random, but for large collections of atoms, we can model how much remains of the original matter after a certain time.


The equation for radioactive decay is given by:

![Radioactive Decay Equation](https://latex.codecogs.com/png.latex?N(t)%20=%20N_0e^{-\lambda%20t})

Where:

- `N(t)` is the quantity of the substance at time `t`.
- `N_0` is the initial quantity of the substance.
- `λ` is the decay constant, specific to each substance.
- `t` is the time that has passed.
- `e` is the base of the natural logarithm.


## Decay Constant Calculation

The decay constant (λ) represents the probability of decay of a radioactive nucleus per unit time. It is related to the **half-life** of the radioactive substance, which is the time required for half of the material to decay.

 -  **Short half-life**: Isotopes with a short half-life are highly unstable and decay rapidly. They may release significant energy in a short period.
 -  **Long half-life**: Isotopes with a long half-life are less unstable, meaning they decay more slowly, sometimes over millions or billions of years. However, they still transform into more stable forms over time.

In summary, stable materials do not undergo radioactive decay, while unstable materials (radioactive isotopes) decay over time, with the half-life determining how quickly or slowly that process occurs. The half-life is a key metric that reflects the degree of instability of a material.

### Formula for Decay Constant:

![Decay Constant Formula](https://latex.codecogs.com/png.latex?\lambda%20=%20\frac{\ln(2)}{T_{1/2}})

Where:
- `λ` is the decay constant (in units of time⁻¹, e.g., per second).
- `T₁/₂` is the **half-life** of the substance (the time required for half of the material to decay).
- `ln(2) ≈ 0.693` is the natural logarithm of 2.


## Features

- Calculates the decay constant from the half-life of the isotope.
- Computes the remaining mass of the isotope after a specified time.
- Plots the decay curve using Matplotlib, showing the mass remaining over time.


## Requirements

* Python 3.8.3

To run this project, ensure you have the following libraries installed:

- `matplotlib`

You can install the required library using pip:

```bash
pip install matplotlib
```

## How to Run

1- Clone the repository or download the script.

2- Install the necessary Python dependencies (see Prerequisites).

3- Run the script by executing the following command in your terminal:

```bash
python radioactive_decay.py
```
4- Enter the half-life of the isotope, the initial mass and the given time, and the program will output the remaining mass and will plot a figure with the corresponding radioactive decay.

