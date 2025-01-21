# Motion-Artifact-Signal-Generation-Toolkit

Motion Artifact Simulation

Authors: 
Jonathan Kulpa
Carleton University, Ottawa, ON, Canada.
Emma Farago
Carleton University, Ottawa, ON, Canada.
Adrian D.C. Chan
Carleton University, Ottawa, ON, Canada. 
University of Ottawa, Ottawa, ON, Canada.
Bruyere Research Institute, Ottawa, ON, Canada.

When citing this resource, cite the original paper:
E. Farago, A.D.C. Chan, Simulating Motion Artifact Using an Autoregressive Model for Research in Biomedical Signal Quality Analysis, 2020 42nd Annual International Conference of the IEEE Engineering in Medicine and Biology Society (EMBC), IEEE, 2020.

This package has been designed to generate simulated motion artifact data using one of three models: Auto Regressive (AR) model, Markov Chain (MC) model, or Recurrent Neural Network (RNN) model.

For all three models, you have the option of downloading a pre-simulated motion artifact signal, using a pre-trained model to synthesize a motion artifact signal, or train a model and simulate a motion artifact signal. The python notebooks have been written for use in Google Colab. Each Python notebook has instructions on how to train and save the models, and simulate and save the synthesized signals.

The input signals used for the pre-trained models and simulated motion artifact signals were recorded using a bioradio acquisition device. 

Arm Movement:
Starts with BR (for bioradio)
Metronome-directed trials were conducted, by defining each half-cycle or point of maximum
shoulder flexion and maximum shoulder extension as coincident with a metronome beat. A set
consisting of three trials was performed in the following order: 85, 100, 120 metronome beats
per minute (bpm) (i.e., 42.5, 50, and 60 complete cycles per minute.

Walking:
Starts with W (for walking)
A set of metronome-directed trials were performed in the following order: 85, 100, and 120
steps (i.e., half a gait cycle) per minute. These trials were designed to represent slow,
moderate, and brisk walking paces.
Each recording was performed with 2 electrode channels.

Hence, the data setup looks like:
BR_S1_85_Ch1 (arm movement, subject 1, 85 bpm, channel 1)
