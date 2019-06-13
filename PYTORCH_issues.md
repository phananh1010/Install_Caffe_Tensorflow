Conda is one of the most convinient way to install pytorch. If you have conda in your system, then installing Pytorch is just in few steps.

Step1: create & activate conda environment:

`conda create -n env_torch python=2.7`
`conda activate env_torch`

Step 2: install pytorch packages

`conda install pytorch-cpu torchvision-cpu -c pytorch`

Step 3: check environment path to see if the packages have been installed

`conda list`
`which python`

Note: recently, conda automatically activate base environment. This maybe annoying since your environment path will be overrided by the base environment.
To force conda to use your customize environment path, use the following command:

`conda config --set auto_activate_base false`
