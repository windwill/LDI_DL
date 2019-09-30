# LDI_DL
Deep Learning for Liability Driven Investment

This program is a reinforcement learning example to solve a simplified DB pension plan dynamic LDI strategy optimization. It is part of the research project "Deep Learning for LDI" sponsored by the Society of Actuaries. The program is intended for educational purpose.

It is coded in Python using PyTorch, which is an open source deep learning package.

The program is saved as an Jupyter Notebook has been tested using Python3.7 with Nivida GPUs.

# File Structure 
**Root folder**

test.ipynb: This file uses a neural network model to represent the reward function in reinfrocement learning. It contains ESG, asset and liability projection, model setup and model training. It solves a simple question: given economic conditions, do I need to increase equity allocation (3%), decrease it (-3%) or keep it the same level as before, at each decision time point in the future? More complicated strategy including more asset classes, allocation limits, and other logics can be easily included.

**Subfolder**

input: Files containing model assumptions

# Run Setting
To DO TASK: File "test.ipynb" have comments about the inputs and run parameters that can be revised according to users' preference. 


# Run Program
1. To run model, open the notebook with Jupyter Notebook and conduct the run.
2. The notebook can also be saved as a py file and can be run using "python test.py"

# Input Folder
It contains some csv files that are used by the program as inputs. File "test.csv" contains a sample of pregernarated scenarios for model training. The program contains scenario generation codes to generate more scenarios in real training. 
