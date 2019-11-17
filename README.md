# App_Schroedinger
 - Numerical simulations of the Schroëdinger equations with python notebooks ('.ipnyb' files). 
 
# How to run the simulations
 - Click on the binder icon to launch the jupyter notebooks online (it can be slow to run).
 
[![Binder](https://mybinder.org/badge_logo.svg)](https://gke.mybinder.org/v2/gh/MQPhysique3EPL/App_Schroedinger/master)

or 

- Download the notebooks on your computer and install the required python packages listed in "requirement.yml". The easiest way is to install Anaconda (www.anaconda.com). Then, with the anaconda prompt, install the libraries with the following command: "conda install -c conda-forge ipywidgets ipympl matplotlib numpy scipy pandas appmode". Next, open anaconda and launch the jupyter notebook subprogram. Finally, open one of the four python notebooks.

- For each program, there is a "script" version (procedural programming) and a "widget" version (more object oriented and more interactive but could be unstable...)

- For the script versions, execute each cell one at a time and respond to the prompt questions

- For the widget versions, either execute all the cells or clic on the "appmode" button

# The 4 python notebooks: 

 - Script_Schrödinger_Ind: 
  Numerical resolution of the time-independant Schrödinger equation for various potentials (sequential programming).
 
 - Widget_Schrödinger_Ind:
    Numerical resolution of the time-independant Schrödinger equation for various potentials (continuous update of the parameters). 

- Script_Schrödinger_Dep:
  Time evolution of a wave packet: numerical resolution of the time-dependant Schrödinger equation (sequential programming).

- Widget_Schrödinger_Dep:
 Time evolution of a wave packet: numerical resolution of the time-dependant Schrödinger equation.
 Push the 'compute' button after selection of the potential and its parameters. 
 Once the simulation is complete (see the hourglass in the tab), you can use the time slider or the player to see the wave packet evolution
 !! If you want to change the potential and/or its parameters, press the 'hold' button first. Otherwise it will compute on the fly the new evolution as you change the parameters. !!!

