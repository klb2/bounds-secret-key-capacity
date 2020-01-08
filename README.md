# Bounds on the Secret Key Capacity

This repository is part of the publication "Bounds on the Ergodic Secret-Key
Capacity for Dependent Fading Channels" (Karl-Ludwig Besser and Eduard
Jorswieck, 24th International ITG Workshop on Smart Antennas, 2020).

## Usage
The calculations are provided in a Mathematica notebook and a Python/Jupyter
notebook.  
If you do not have a Jupyter installation, you can also run it online.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gl/klb2%2Fbounds-secret-key-capacity/master?filepath=Bounds%20on%20the%20Ergodic%20Secret%20Key%20Capacity.ipynb)

### Local Installation
If you want to run the files locally, make sure you have 
[Python3](https://www.python.org/downloads/) installed on your computer.

You can install the requires packages (including Jupyter) by running
```
pip3 install -r requirements.txt
jupyter nbextension enable --py widgetsnbextension
```
This will install all the needed packages which are listed in the requirements 
file. The second line enables the interactive controls in the Jupyter
notebooks.

Afterwards, you can start the notebook by running
```
jupyter notebook 'Bounds on the Ergodic Secret Key Capacity.ipynb'
```
