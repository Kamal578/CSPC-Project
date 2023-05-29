# NMR Spectrum Analysis

This repository contains a Python script (`main.py`) for analyzing NMR spectra of different chemical compounds. The script performs several tasks, including plotting the NMR spectra, identifying peaks in the spectra, estimating initial concentrations of compounds, analyzing the evolution of compound concentrations over time, and calculating the reaction constant *k*.

## Authors

- [Murad Mustafayev](https://github.com/Muradmustafayev-03)
- [Kamal Ahmadov](https://github.com/Kamal578)

## Usage

To use the script, follow the steps below:

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/your-repository.git
    ```

2. Navigate to the repository:

    ```bash
    cd your-repository
    ```

3. Run the script:

    ```bash
    python main.py
    ```

## Dependencies

The `main.py` script performs the following tasks:

1. Imports the necessary packages for data analysis and visualization.
2. Loads the NMR data from the provided file.
3. Plots the pure NMR spectra of three compounds: ethanoic acid, propanol, and propyl-ethanoate.
4. Defines a function for identifying peaks in an NMR spectrum.
5. Applies the peak identification function to the spectra of the three compounds.
6. Estimates the initial concentrations of the compounds based on the peaks in the initial spectrum.
7. Analyzes the NMR spectra over time to plot the evolution of compound concentrations during the reaction.
8. Calculates the reaction constant k based on the concentration evolution.

## Results
The script generates plots of the NMR spectra, the evolution of compound concentrations, and calculates the value of the reaction constant k. The calculated value of k is stored in the variable k.

Please refer to the script's output and generated plots for detailed results and visualizations.