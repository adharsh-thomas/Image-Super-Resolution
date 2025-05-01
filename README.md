# Super Resolution Hybrid

A lightweight super-resolution model trained on CIFAR-10 using a hybrid approach (GAN + RRDB + Attention + Multiscale Features).

## Features
- Based on Residual-in-Residual Dense Blocks (RRDB)
- Incorporates attention mechanisms
- Multi-scale feature extraction
- Trained on CIFAR-10 for 10 epochs
- Designed for fast inference and low-resource environments

## Usage
```bash
python superresolutionganhybrid.py
```

## Output Samples
Included:
- SRout.png — Example super-resolved output
- SuperResolutionLOSS.png — Loss curve during training
- HighResBlock.png — Architecture visualization

## Dataset
CIFAR-10 (32x32 images)

## Author
Created by Adharsh (repo will be renamed if needed)
