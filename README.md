# Bounds on the Secret Key Capacity &ndash; Supplementary Material

This repository is part of the publication "[Bounds on the Ergodic Secret-Key
Capacity for Dependent Fading
Channels](https://ieeexplore.ieee.org/document/9097120)" (Karl-Ludwig Besser
and Eduard Jorswieck, 24th International ITG Workshop on Smart Antennas, 2020).

The idea is to give an interactive version of the calculations to the reader
such that one can easily reproduce the plots presented in the paper as well as
changing parameters. One can also use this framework as a baseline and adjust
it to their own needs, e.g., for different channel models.

## File List
The following files are provided in this repository:

* [Bounds on the Ergodic Secret Key
  Capacity.ipynb](https://mybinder.org/v2/gl/klb2%2Fbounds-secret-key-capacity/master?filepath=Bounds%20on%20the%20Ergodic%20Secret%20Key%20Capacity.ipynb):
  Jupyter notebook containing the results for Rayleigh fading presented in the
  paper
* `Bounds-Secret_Key_Capacity-Rayleigh.nb`: Mathematica notebook that contains
  all calculations for Rayleigh fading
* `Bounds-Secret_Key_Capacity-Alpha_Mu.nb`: Mathematica notebook that contains
  all calculations for alpha-mu fading


## Usage
The calculations are provided in a Mathematica notebook and a Python/Jupyter
notebook.  
If you do not have a Jupyter installation, you can also run it online.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gl/klb2%2Fbounds-secret-key-capacity/master?filepath=Bounds%20on%20the%20Ergodic%20Secret%20Key%20Capacity.ipynb)

### Local Installation
If you want to run the files locally, make sure you have 
[Python3](https://www.python.org/downloads/) installed on your computer.

You can install the required packages (including Jupyter) by running
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


## Acknowledgements
This research was supported in part by the Deutsche Forschungsgemeinschaft
(DFG) under grant JO 801/23-1.


## License and Referencing
This program is licensed under the GPLv3 license. If you in any way use this
code for research that results in publications, please cite our original
article listed above.

You can use the following BibTeX entry
```
@inproceedings{Besser2020wsa,
	author = {Besser, Karl-Ludwig and Jorswieck, Eduard A.},
	title = {Bounds on the Ergodic Secret-Key Capacity for Dependent Fading Channels},
	booktitle = {2020 International {ITG} Workshop on Smart Antennas ({WSA})},
	month = {2},
	year = {2020},
	publisher = {VDE},
	url = {https://ieeexplore.ieee.org/document/9097120},
}
```
