# Kappa-Mu-Shadowed-Fading-Python

The \kappa-\mu shadowed fading model implemented in python. Plots the theoretical and simulated envelope porbability density functions (PDFs)

Further details of this model can be found in Paris' paper: 
"Statistical characterization of \kappa-\mu shadowed fading".

This project uses PySimpleGUI, numpy, matplotlib and tkinter.

This project was developed on a windows OS, using Spyder IDE with Python 3.8. All the dependencies where installed by anaconda.

The input \kappa accepts values in the range 0 to 50.
The input m accepts values in the range 0.001 to 50.
The input \mu accepts integer values in the range 1 to 10.
The input \hat{r} accepts values in the range 0.5 to 2.5.

Runing main.py to start the GUI:
  
![ScreenShot](https://raw.github.com/Jonathan-Browning/Kappa-Mu-Shadowed-Fading-Python/main/docs/window.png)

Entering values for \kappa, m, \mu, and the root mean sqaure of the signal \hat{r}:

![ScreenShot](https://raw.github.com/Jonathan-Browning/Kappa-Mu-Shadowed-Fading-Python/main/docs/inputs.png)

The theoretical evenlope PDF is plotted to compare with the simulation and gives the execution time for the theoretical calculation and simulation together:

![ScreenShot](https://raw.github.com/Jonathan-Browning/Kappa-Mu-Shadowed-Fading-Python/main/docs/results.png)
