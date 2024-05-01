# Setup Instructions

## Overview
This document provides detailed instructions on how to set up and run the Crypto Trading Risk Management System on your local machine. Follow these steps to configure your development environment and start using the system.

## Prerequisites
Before you begin, ensure you have the following installed:
- Python 3.8 or higher
- Git
- pip (Python package installer)

## Cloning the Repository
To get started, clone the repository to your local machine. Open your terminal and run the following command:
```bash
git clone https://github.com/BoothP/crypto-trading-system
cd crypto-trading-system

## Environment Setup
It's recommended to use a virtual environment to isolate package dependencies. To set up and activate a virtual environment, run:
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

## Installing Dependencies
Install all required Python packages by running:
pip install -r dependencies/requirements.txt

## Configuration
To configure the system, follow these steps:

Navigate to the src directory.
Rename config.sample.py to config.py.
Edit config.py to include your specific settings such as API keys, trading parameters, and database connection strings (if applicable).

## Running the System
To run the system, ensure you are still in the src directory and then execute:
python trade_executor.py

## Additional Notes
Always ensure your API keys and sensitive data are stored securely and not hard-coded in scripts.
Regularly update your dependencies to keep your system secure.

## Troubleshooting
If you encounter any issues with installation, first ensure your virtual environment is activated and that you have the correct permissions to install packages.
For specific script errors, check the Python error log provided in the console for hints on what might be wrong.
Thank you for setting up the Crypto Trading Risk Management System. For further assistance, please open an issue on the GitHub repository.
