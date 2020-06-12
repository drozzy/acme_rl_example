# acme_rl_example

Simple example of acme RL library. Takes the official colab tutorial https://github.com/deepmind/acme/blob/master/examples/tutorial.ipynb and makes it runnable with all the necessary dependencies (except for jax and mujoco).

## Installation

1. Install apt-get dependency

       sudo apt-get install -y xvfb     

2. Create conda env with all necessary dependencies:

       conda env create -f environment.yml

3. Activate the environment

       conda activate acme-rl-example

4. Lunch Jupyter and run the notebook:

       jupyter notebook
