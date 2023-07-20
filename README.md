---


---
## Overview

This project implements the Gillespie algorithm to simulate a chemical reaction network consisting of three species: A, B, and C. The simulation runs for a total time of 50.0 seconds and outputs the molecule counts for each species at every second.

## Features

* Implementation of the Gillespie algorithm for simulating chemical reactions
* Support for customizing the rate constants, initial molecule counts, and simulation time
* Outputs the molecule counts for each species at every second during the simulation
* Uses NumPy for efficient array operations
* Includes a visualization of the simulation using Matplotlib

## Usage

1. Clone this repository and install the required dependencies:

```bash
git clone https://github.com/your-username/gillespie-algorithm-simulation.git
cd gillespie-algorithm-simulation
pip install -r requirements.txt
```

2. Run the simulation using the following command:

```bash
python simulate.py
```

3. The output will be saved in a CSV file named** **`output.csv`. You can view the plot of the simulation by running:

```bash
python plot.py
```

4. To customize the simulation parameters, modify the corresponding variables at the beginning of the** **`simulate.py` file.

## Parameters

* `rate_A_to_B`: the rate constant for the reaction A -> B (default: 1.0)
* `rate_B_to_C`: the rate constant for the reaction B -> C (default: 0.5)
* `initial_A`: the initial number of molecules of species A (default: 100)
* `initial_B`: the initial number of molecules of species B (default: 0)
* `initial_C`: the initial number of molecules of species C (default: 0)
* `simulation_time`: the duration of the simulation (default: 50.0)

## Contributing

Contributions are welcome! If you would like to contribute to this project, please fork it and submit a pull request with your changes.

## License

This project is licensed under the MIT License. See LICENSE.txt for details.

## Acknowledgments

Thank you to Dr. William Richardson, University of Arkansas for their contributions and support.
