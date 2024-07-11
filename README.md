# High-Frequency Trading (HFT) Simulation Project

## Overview

This project simulates a high-frequency trading environment, providing tools for data generation, trading algorithm implementation, backtesting, and performance optimization. It's designed to help researchers and traders develop and test HFT strategies in a controlled environment.

## Features

- Synthetic market data generation
- Real-time data streaming simulation
- Implementation of various trading algorithms
- Performance optimization tools
- Comprehensive backtesting framework
- Data analysis and visualization tools

## Setup

1. **Clone the repository**:

	```sh
	git clone https://github.com/yourusername/hft_simulation_project.git
	cd hft_simulation_project

2. **Create a virtual environment (optional but recommended)**:

	```sh
	python -m venv venv
	source venv/bin/activate #For Windows: venv\Scripts\activate

3. **Install the required dependencies**:

	```sh
	pip install -r requirements.txt


## Usage

1. **Generate market data**:

	```sh
	python scripts/generate_market_data.py

2. **Run a simulation**:

	```sh
	python scripts/run_backtest.py

3. **Perform backtesting**:

	```sh
	python scripts/run_backtest.py

4. **For data analysis and visualization, open the Jupyter notebooks in the `notebooks/` directory**:

	```sh
	jupyter notebook notebooks/


## Configuration

Adjust the parameters in `config/config.yaml` to customize the simulation settings, data generation parameters, and algorithm configurations.

## Testing

Run the unit tests to ensure all components are functioning correctly:

	```sh
	python -m unittest discover tests

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- [List any libraries, papers, or resources that significantly influenced this project]
