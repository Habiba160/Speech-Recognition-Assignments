# Speech Recognition Assignments

This repository contains the implementation of five speech recognition assignments covering the fundamental concepts of speech signal processing, feature extraction, probabilistic modeling, and sequence modeling. The assignments were implemented in Python as part of a Speech Recognition course.

## Topics Covered

### Assignment 1 – Speech Signal Analysis

* Audio loading and preprocessing
* Loudness (intensity) extraction
* Fundamental frequency (pitch/F0) estimation
* Fast Fourier Transform (FFT)
* Frequency spectrum visualization
* Waveform and sinusoidal component analysis
* Short-Time Fourier Transform (STFT)
* Spectrogram generation
* Formant and phoneme analysis
* Effect of different window sizes and overlaps on time-frequency resolution

### Assignment 2 – Mel Spectrogram Analysis

* Male vs. female speech comparison
* Mel Spectrogram computation
* Mel Filter Bank visualization
* Spectral energy distribution analysis
* Fundamental frequency (F0) comparison
* Formant pattern analysis
* Discussion of acoustic differences
* Applications in speech recognition and speaker identification

### Assignment 3 – Speaker Identification using Gaussian Mixture Models (GMM)

* MFCC and Mel Filter Bank feature extraction
* Custom implementation of the Expectation-Maximization (EM) algorithm
* Gaussian Mixture Model (GMM) training for each speaker
* Speaker identification using maximum likelihood estimation
* Evaluation on the VCTK speech corpus

### Assignment 4 – Hidden Markov Models (HMM) for Word Recognition

* MFCC feature extraction
* HMM training using the `hmmlearn` library
* Inspection of transition, emission, and initial probability matrices
* Custom implementation of the Forward algorithm
* Custom implementation of the Viterbi algorithm
* Word likelihood computation
* Most likely phoneme sequence decoding
* Evaluation using the TIMIT speech corpus

### Assignment 5 – Hidden Markov Model Direct Computation

* Manual computation of HMM observation probabilities
* State sequence (path) enumeration
* Joint probability calculation
* Total probability via direct path summation
* Complexity analysis of HMM path enumeration

## Technologies Used

* Python
* NumPy
* SciPy
* Librosa
* Matplotlib
* hmmlearn
* Jupyter Notebook

## Learning Outcomes

This repository demonstrates practical implementations of the core algorithms used in modern speech processing systems, including:

* Speech signal analysis
* Spectral feature extraction
* FFT and STFT
* Mel Spectrograms
* MFCCs
* Gaussian Mixture Models (GMM)
* Expectation-Maximization (EM)
* Hidden Markov Models (HMM)
* Forward Algorithm
* Viterbi Algorithm
* Speaker Identification
* Word Recognition

Each assignment was implemented to strengthen the understanding of both the mathematical foundations and practical applications of speech recognition systems.
