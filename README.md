# Bayesian mixture model (Bmix) for tropical cyclone precipitation

### Introduction

This is a PyMC implementation of our work on *Bayesian typhoon precipitation prediction with a mixture of ensemble forecast-based and historical event-based prediction functions*. [Paper](https://doi.org/10.1016/j.jhydrol.2024.131176).

It is recommended that the code be opened and viewed using the Chrome browser.

Additionally, it is strongly recommended to open and try it on Google Colab: [Colab link](https://colab.research.google.com/drive/1gVprj2XB4SsrigfRp5uobZmKFVx5VNOa?usp=drive_link)

The code provides probability density for the predicted weather variable. For more details, please see [Bmix_Code](https://github.com/yvminyni/Bmix/blob/main/Bmix_Code_notebook.ipynb).


### Requirements
```
Python 3.8.x or greater. (Tested with 3.10.12)
IPython (Tested with 7.34.0)

pymc      : 5.7.2
arviz     : 0.15.1
pandas    : 1.5.3
scipy     : 1.11.4
numpy     : 1.23.5
matplotlib: 3.7.1

```

For more PyMC installation details, please follow the [installation guide](https://www.pymc.io/projects/docs/en/stable/installation.html).


### Citation
If you use this code, please consider citing the following [paper](https://doi.org/10.1016/j.jhydrol.2024.131176):

	@article{hyj23,  
	  journal        = {Journal of Hydrology}  
	  title          = {Bayesian Typhoon Precipitation Prediction with a Mixture of Ensemble Forecast-based and Historical Event-based Prediction Functions},
	  author         = {Yu-Jyun Huang, Yi-Yun Lee, Hui-Ling Chang, Charlotte Wang, Jing-Shan Hong, & Chuhsing Kate Hsiao}
	  year           = {2024},
	  volume         = {635}
	}
 <!--Huang Yu-Jyun 2024 -->    <!--{Journal of Hydrology},-->

### License

[MIT License](https://github.com/yvminyni/Bmix/blob/main/LICENSE)
