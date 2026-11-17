# IMsc-2025
This notebook contains all code nescessary to replicate the figures in the paper "Mpemba effect in a chemomechanical model of the
Kinesin molecular motor" by Karthik Cheruvary and Arnab Pal. To run this, you will need to have Julia installed.

For macOS or Linux this can be done by running the following command in the terminal:

```curl -fsSL https://install.julialang.org | sh```

For Windows, run this command in the terminal:
```winget install --name Julia --id 9NJNWW8PVKMN -e -s msstore```

Further details can be found at https://julialang.org/downloads/

You will also need some packages to run this notebook. These are present in an environment. Activate this by running 
```julia --project=.```. This should open a Julia REPL in an environment with all the required packages installed. In the REPL, run ```notebook(dir = pwd())``` and select the notebook
