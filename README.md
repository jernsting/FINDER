# FINDER (FInding key players in complex Networks through DEep Reinforcement learning)


## Contents

- [Overview](#overview)
- [Repo Contents](#repo-contents)
- [System Requirements](#system-requirements)
- [Installation Guide](#installation-guide)
- [Reproduction instructions](#reproduction-instructions)
- [Basebline methods implementation](#basebline-methods-implementation)

# Overview

Finding an optimal set of nodes, called key players, whose activation (or removal) would maximally enhance (or degrade) certain network functionality, is a fundamental class of problems in network science. Potential applications include network immunization, epidemic control, drug design, and viral marketing. Due to their general NP-hard nature, those problems typically cannot be solved by exact algorithms with polynomial time complexity. Many approximate and heuristic strategies have been proposed to deal with specific application scenarios. Yet, we still lack a unified framework to efficiently solve this class of problems. Here we introduce a deep reinforcement learning framework FINDER, which can be trained purely on small synthetic networks generated by toy models and then applied to a wide spectrum of influencer finding problems. Extensive experiments under various problem settings demonstrate that FINDER significantly outperforms existing methods in terms of solution quality. Moreover, it is several orders of magnitude faster than existing methods for large networks. The presented framework opens up a new direction of using deep learning techniques to understand the organizing principle of complex networks, which enables us to design more robust networks against both attacks and failures. 

# Repo Contents

- [code]: including 'FINDER_CN', 'FINDER_CN_cost', 'FINDER_ND' and 'FINDER_ND_cost', four agents to reproduce the results reported in the manuscripte. 
- [data]: including synthetic data and real data used in the paper.
- [environment]: including the Docerfile, which can be directly used if using docker environment.



# System Requirements

## Software dependencies and operating systems

Users should install the following packages first, which will install in about 5 minutes on a machine with the recommended specs.

The versions of software are, specifically:
```
cython==0.29.13 
networkx==2.3 
numpy==1.17.3 
pandas==0.25.2 
scipy==1.3.1 
tensorflow-gpu==1.14.0 
tqdm==4.36.1
```

The developmental version of the package has been tested on the following systems:

Linux: Ubuntu 16.04  
Windows:  10

## Hardware Requirements

`FINDER` requires only a standard computer with enough RAM to support the operations defined by a user. For minimal performance, this will be a computer with about 10 GB of RAM. For optimal performance, we recommend a computer with the following specs:

RAM: 16+ GB  
CPU: 4+ cores, 3.3+ GHz/core

The runtimes below are generated using a computer with the recommended specs (16 GB RAM, 4 cores@3.3 GHz) and internet of speed 25 Mbps.


# Installation Guide

## Instructions
1. First install the required packages, which are contained in the requirements.txt file
```
pip install -r requirements.txt
```
2. Make all the file
```
python setup.py build_ext -i
```

## Typical install time
It took about 5 mins to install all the required packages, and about 1 mins to make all the files

# Reproduction instructions

## Instructions to run on data
1. To train all the model

### Train

### Test synthetic data

### Test real data


## Expected output

## Expected run time



# Basebline methods implementation

