# fair4jndemo
FAIR for Jupyternotebook


## Code dependencies 

The code dependencies are captured in the environment.yaml file. The instructions about create one for your project can be found at the link below.

https://mybinder.readthedocs.io/en/latest/howto/languages.html

To get the list of python packages and dependencies use the following commands in jupyter notebook. This inststruction commands are not part of the notebook .pynb file. 

! freeze

! freeze | grep -i numpy # getting numpy version only.

! freeze | grep -i matplotlib # getting matplotlib version only. 
