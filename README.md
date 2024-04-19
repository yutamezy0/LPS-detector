[![DOI](https://zenodo.org/badge/788858272.svg)](https://zenodo.org/doi/10.5281/zenodo.10996506)
# LPS-Detector
A CNN-based automatic detection model for Later Phase in S coda (LPS), which was observed at near-source stations of earthquakes occurring in the upper crust.  
## Installing
Download LPS-detector repository

```
git clone https://github.com/yutamezy0/LPS-detector.git
```

Install to virtual envirionment

```
conda env create -f lpsd.yml
```

## Contents
### lpsdetector.ipynb
:  Jupyter Notebook for operating the LPS-detector
### lpsdetector_modelweight.h5
:  Trained model parameters 
### list_label.txt
:  Event list with LPS label (1: with LPS / 0: without LPS) for training dataset used in <sup>[1]</sup> Amezawa et al. (in prep)
## Usage
1. Prepare waveform files in SAC format for the two horizontal components of the velocity seismograms.\
(Default: independent directories for N-S and E-W component seismograms under the waveform directory)

2. Change the path for input seismograms in lpsdetector.ipynb and run the code.

## Reference
Reference publication for LPS-detector:\
[1] Amezawa, Y., Uchide, T., Shiina, T., Ogata, J., Fukayama, S., and Kuroda, H. "LPS-detector: Convolutional Neural Network Based Automatic Detection Model for Later Phase in S coda" (in prep.)

## Acknowledgement
The initial version of the LPS-detector has been developed under the support of the MEXT Project for Seismology toward Research Innovation with Data of Earthquake (STAR-E) Grant Number JPJ010217.
