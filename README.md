## Project Description
We aim to learn patterns in DNA sequences and classify them based on whether or not a protein will bind to them, thus facilitating gene regulation. 
Specifically, we model a Convolutional Neural Network to detect patterns in DNA Sequences which cause certain Transcription Factors (TF's) to bind to regulatory sites.

For more information, link to our final presentation: https://bit.ly/2Y2a4L4

## Requirements
Project is done in Python 3 environment.
The training was done on a NVIDIA Quadro M2000 GPU with 32GB RAM.

Open Source Libraries used - 
1. Keras - https://github.com/keras-team/keras
2. Numpy - https://github.com/numpy/numpy
3. Pandas - https://github.com/pandas-dev/pandas
4. Matplotlib - https://github.com/matplotlib/matplotlib
5. DeepLift - https://github.com/kundajelab/deeplift


## Description of Important Files 

1. `DeepBind_Code.ipynb` - The main processing file which takes the FASTA / CSV files for training and then trains the CNN. Also includes the visualisation and computing of importance scores with the help of DeepLift.


##  Steps to run on Local Machine

1. Make sure Anaconda is installed on your machine

2. Open the `DeepBind_Code.ipynb` file and run through jupyter notebook
