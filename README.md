# LPS-Detector
A CNN-based automatic detection model for Later Phase in S coda (LPS), which was observed at near-source stations of earthquakes occurring in the upper crust.  
## Installing
Download LPS-detector repository
git clone https://github.com/yutamezy0/LPS-detector.git

Install to "phasenet" virtual envirionment
conda env create -f lpsd.yml
conda activate lpsd

## Usage
1. Prepare waveform files in SAC format for the two horizontal components of the velocity seismograms.
(Default: independent directories for N-S and E-W component seismograms under the waveform directory)

2. Change the path for input seismograms in lpsdetector.ipynb and run the code.

## Related paper
Amezawa, Y., Uchide, T., Shiina, T., Ogata, J., Fukayama, S., and Kuroda, H. "LPS-detector: Convolutional Neural Network Based Automatic Detection Model for Later Phase in S coda" (in prep.)
