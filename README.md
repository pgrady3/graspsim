# graspsim
Pybullet grasping simulator

Stock pybullet examples are in the examples folder

## Installation
My computer is using a GTX 1080 TI, NVIDIA driver 384.130, CUDA 9.0, cuDNN 7.0

First create a new conda environment. Note that we require some old versions of packages, because of my old versions of NVIDIA stuff. This should be fixed later
```
conda create --name sim
conda activate sim
conda install python=3.6
```

Then install the requisite packages
```
pip install gym
pip install pybullet
pip install tensorflow-gpu==1.8.0
```
Helpful to install OpenAI baselines. Note that the compatibility between pybullet examples and OpenAI baselines isn't great, and some stuff has to be modified.

```
git clone https://github.com/openai/baselines.git
cd baselines
pip install -e .
```
