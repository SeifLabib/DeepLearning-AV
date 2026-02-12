# Deep Learning for Autonomous Vehicles

This repository contains all the labs & projects, I have completed in the course [Deep Learning for Autonomous Vehicles (DLAV)](https://edu.epfl.ch/coursebook/fr/deep-learning-for-autonomous-vehicles-CIVIL-459). It goes all the way from the introduction notebooks, to actual exercises, introducing neural network models and many other notebooks.

## Developing Virtual Environment

```
conda create --name DLAV python=3.11 

conda activate DLAV
```

For the packages, I chose this one since I have a NVIDIA GPU (for CUDA acceleration and whatnot).
```
conda install pytorch torchvision torchaudio pytorch-cuda=12.1 -c pytorch -c nvidia
```

If this was not the case (ie. for CPU only, no dedicated GPU), this command should do the trick.
```
conda install pytorch torchvision torchaudio cpuonly -c pytorch
```

And the installing other common packages.
```
conda install pandas matplotlib scikit-learn tqdm
conda install ipykernel
```