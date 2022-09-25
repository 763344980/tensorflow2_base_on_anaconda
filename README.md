# tensorflow2_base_on_anaconda
This project is using for training tensorflow2.0 by using python which is included in Anaconda that inclouding such package like numpy、scipy、pandas and others.

In the first step,most of all,download Anaconda.

In this project,Anaconda has been setted in newest version.

Setting step will not be shown in this Readme,Because it can be find at interet everywhere,and it is too easy to set just like setting WOW or the other software

--------------------------------------------------------Setting tensorflow 2.0 or higher-------------------------------------------------------------------
U can choose use base or the virtual，and i will use base.

Create an virtual environment：(If you are using windows,of caurse you are,follow this steps.If you are using linux or MacOS,you could using ohter tools which batter than Anaconda——create yourself environment——different system ways will be added in this readme someday)

1.Order "conda create -n tenserflow_env python = 3.6.0"  will create an environment that be named tenserflow_env,and using python 3.6,if you want rename it or using different python version,change it.

2.Check your GPU by use "nvidia-smi",make sure your Driver Version higher than 410.x.If you want to set an not-GPU version, pass this step

3.if in the step 1 you created an virtual environment you need using "activate tensorflow_env" to activate it,and than install cudatoolkit and cudnn by "conda install cudatoolkit" and "conda install cudnn=7.6.0",by the same way,you could change cudnn's version,by same way,if you are setting an not-GPU version,pass install cudatoolkit and cudnn

4.install tensorflow. use "pip install tensorflow-gpu==2.0.0" to install GPU version tensorflow.use "pip install tensorflow==2.0.0" to install not-GPU version tensorflow. Here will show an error because 2.0.0 is not avaliable to downding you can choose ohter version in " 2.5.0, 2.5.1, 2.5.2, 2.5.3, 2.6.0, 2.6.1, 2.6.2, 2.6.3, 2.6.4, 2.6.5, 2.7.0rc0, 2.7.0rc1, 2.7.0, 2.7.1, 2.7.2, 2.7.3, 2.7.4, 2.8.0rc0, 2.8.0rc1, 2.8.0, 2.8.1, 2.8.2, 2.8.3, 2.9.0rc0, 2.9.0rc1, 2.9.0rc2, 2.9.0, 2.9.1, 2.9.2, 2.10.0rc0, 2.10.0rc1, 2.10.0rc2, 2.10.0rc3, 2.10.0"

5.Using jupyter notebook or the other tools to check installing is succeeded or not. 
example in jupyter: 1.import tensorflow as tf 2.tf.__version__ 3.tf.test.is_gpu_available()

WARRNING:MAKE SURE THAT YOUR TENSORFLOW'VERSION IS FITTING IN cuDNN's version and cudatoolkit's verison.

----------------------------------------------------------------------------------end-----------------------------------------------------------------------
