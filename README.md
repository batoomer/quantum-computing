# Quantum Computing

## Introduction

This project aims to provide an introduction to quantum computing concepts and implementation through a collection of Jupyter notebooks and Python scripts. The goal is to provide an accesible and easy-to-use resource for those intersted in learning about quantum computing and its applications

The repository contains a variety of notebooks that cover different topics:
* Quantum Bit 
* Quantum Register
* Quantum Circuits
* Quantum Algorithms

If you have any questions or feedback, please feel free to contact us.

## Installation

To get started folow these steps:

1. Install Anaconda: If you don't already have Anaconda installed, you can download it from the official Anaconda website (https://www.anaconda.com/products/individual). Follow the installation guide for your operating system to install Anaconda.

2. Clone the repository: Once you have Anaconda installed, you can clone our repository from GitHub using the following command in your terminal:
    ```zsh
    git clone https://github.com/your-username/quantum-computing.git
    ```
    Replace "your-username" with your GitHub username.

3. Create a virtual environment: It's recommended that you create a virtual environment for this project to avoid conflicts with other Python packages. To create a new virtual environment, navigate to the root directory of the cloned repository in your terminal and run the following command:
    ```zsh
    conda create --name qc-env python=3.8
    ```

    This will create a new virtual environment named "qc-env" with Python version 3.8.

4. Activate the virtual environment: Once the virtual environment is created, activate it by running the following command:
    ```zsh
    conda activate qc-env
    ```

5. Install dependencies: With the virtual environment activated, install the necessary dependencies by running the following command:
    ```zsh
    pip install -r requirements.txt
    ```

    Now, you should have all the necessary dependencies installed to run our quantum computing notebooks and scripts.

If you encounter any issues during the installation process, please refer to the official Anaconda installation guide or contact us for assistance.

## Usage

To use the repository, follow these steps:

1. Activate the virtual environment: Before running any of the notebooks or scripts, make sure to activate the virtual environment you created during the installation process by running the following command in your terminal:
    ```zsh
    conda activate qc-env
    ```

2. Launch Jupyter Lab: To run the Jupyter notebooks, navigate to the "notebooks" directory in your terminal and launch Jupyter Lab by running the following command:
    ```zsh
        jupyter lab
    ```

    This will open a new tab in your web browser with the Jupyter Lab interface. From there, you can navigate to the individual notebooks and open them to view and run the code.

3. Run Python scripts: To run the Python scripts located in the "src" directory, simply navigate to the directory in your terminal and run the desired script using the Python interpreter. For example, to run a script named "my_script.py", run the following command:
    ```zsh
    python my_script.py
    ```
    This will execute the script and output the results to your terminal.

Note: Some of the notebooks and scripts may require additional setup or configuration, such as specifying the backend for running quantum circuits. Please refer to the specific instructions provided in the individual notebooks and scripts for more information.

## License:

This project is released under the MIT License.

You can find the full text of the MIT License in the LICENSE file in the root directory of this repository.





