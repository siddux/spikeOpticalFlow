# Spike Optical Flow

## Overview

This repository contains the code for the work on Optical Flow Estimation using Hybrid Neural Network. The code below is derived from the original implementation by Parts of this code were derived from [chan8972/Spike-FlowNet](https://github.com/chan8972/Spike-FlowNet).

## Installation
Clone the repository using: 
```git clone https://github.com/siddux/spikeOpticalFlow.git```

Create a conda environment using the [environment.yml](environment.yml) file: 
```conda env create -f environment.yml```

Activate the conda environment: 
```conda activate spikeopticalflow```


## Dataset

The datasets used for train and test this neural network are large so they can't be uploaded to this repository. As soon as possible they will be uploaded to Google Drive and the links will be available on the remote version of this repo [siddux/spikeOpticalFlow](https://github.com/siddux/spikeOpticalFlow).


## Training

The basic syntax for training the neural network is:

```python3 main.py```



## Pre-trained Model

The pretrained model can be found in [/pretrain](pretrain/) folder.


## Testing

The basic syntax for testing is:

```python3 main.py --evaluate --pretrained='./pretrain/checkpoint_dt1.pth.tar' --render --save-images``` 

Another commands are available to change running options in the main file.