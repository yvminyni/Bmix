# Bayesian mixture model (Bmix) for tropical cyclone precipitation

### Introduction

This is a PyMC implementation of our work *Bayesian typhoon precipitation prediction with a mixture of ensemble forecast-based and historical event-based prediction functions* [Submitted](link).

It is recommended that the code be opened and viewed using the Chrome browser.

Additionally, it is strongly recommended to open and try it on Google Colab: [Colab link](https://colab.research.google.com/drive/1gVprj2XB4SsrigfRp5uobZmKFVx5VNOa?usp=drive_link)

The code provides probability density for the predicted weather variable. For more details, please see [Bmix_Code](https://github.com/yvminyni/Bmix/blob/main/1130_Bmix_Code.ipynb).


### Requirements
```
Python 3.8.x or greater. (Tested with 3.10.12)
IPython (Tested with 7.34.0)

pandas    : 1.5.3
scipy     : 1.11.3
matplotlib: 3.7.1
seaborn   : 0.12.2
numpy     : 1.23.5
arviz     : 0.15.1
pymc      : 5.7.2
```

For more PyMC installation details, please follow the [installation guide](https://www.pymc.io/projects/docs/en/stable/installation.html).


### Citation
If you use this code, please consider citing the following paper:

	@article{hyj23,  
	  journal        = {Submitted}  
	  title          = {Bayesian typhoon precipitation prediction with a mixture of ensemble forecast-based and historical event-based prediction functions},
	  author         = {Yu-Jyun Huang, Yi-Yun Lee, Hui-Ling Chang, Charlotte Wang, Jing-Shan Hong and Chuhsing Kate Hsiao}
	  year           = {2023},
	  volume         = {-},
	  pages          = {-}
	}
 <!--Huang Yu-Jyun 2023? I guess-->    <!--{Journal of Hydrology},-->
### License

[MIT License](https://github.com/yvminyni/Bmix/blob/main/LICENSE)
