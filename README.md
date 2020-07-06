# JupyterAudioAnalysis

This repository contains some experiments with audio analysis and Jupyter notebooks.

The Experiments folder contains some basic code that show how to do real time audio analysis in a Jupyter Notebook.

The GuitarSetCaseStudy contains a project where I replicate part of the research efforts carried over by Darren Tio In [1] and Andy Wiggins, Youngmoo E. Kim in [2]. 
The goal is to extract a dataset from GuitarSet and use it to train and validate a model that recognises note patterns in an audio file. 
The key idea is originated in [2] and implies using Complex-Q Transform together with a Convoluted Neural Network for the learning.

The average accuracy obtain is a very interesting 0.9007!

If you are interested to learn more, have a look at the CapstoneProjectProposal.pdf and CapstoneProject.pdf in the root folder, 
which discuss the design and implementation in more deatils.



[1] Darren Tio, Automated Guitar Transcription with Deep Learning. 
Available at https://towardsdatascience.com/audio-to-guitar-tab-with-deep-learning-d76e12717f81
[2] Andy Wiggins and Youngmoo E. Kim, Automatic Guitar Tablature Transcription with Convolutional Neural Networks. 
Available at http://nemisig2019.nemisig.org/images/kimSlides.pdf
