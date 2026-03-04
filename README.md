# Spectral Analysis of Real-World Audio Signals Using Python

This project explores how real-world sounds can be analyzed in the **frequency domain** using signal processing techniques in Python.

By applying Fourier Transform and spectral feature extraction, different sound sources such as **clap, bird calls, and traffic noise** are analyzed and compared.

---

## Objectives

The goal of this project is to understand how real-world signals behave in the frequency domain by extracting key spectral features.

The project demonstrates:

- Time-domain visualization of audio signals
- Frequency-domain analysis using Fast Fourier Transform (FFT)
- Spectrogram visualization
- Extraction of spectral features such as:
  - Dominant frequency
  - Spectral centroid
  - Zero-crossing rate

---

## Tools and Libraries

This project was implemented using:

- Python
- NumPy
- Matplotlib
- Librosa
- Jupyter Notebook

---

## Signals Analyzed

Three real-world signals were analyzed:

1. Clap sound
2. Bird sound
3. Traffic noise

Each signal was analyzed using the same pipeline:
1. Load audio signal
2. Plot waveform (time domain)
3. Compute FFT spectrum
4. Generate spectrogram
5. Extract spectral features

---

## Feature Explanation

**Dominant Frequency**

The dominant frequency represents the frequency with the highest magnitude in the signal's spectrum.

**Spectral Centroid**

The spectral centroid represents the "center of mass" of the spectrum and indicates whether a sound contains more high-frequency or low-frequency energy.

Higher centroid → brighter / sharper sound  
Lower centroid → deeper / bass-heavy sound

**Zero Crossing Rate**

The zero crossing rate measures how often the signal waveform crosses the zero amplitude line.

Higher ZCR → noisy or rapidly varying signals  
Lower ZCR → smoother or periodic signals

---

## Observations

See `summary.txt` for observations.

Key findings include:

- Impulsive sounds like **claps** produce wideband frequency content and high zero-crossing rates.
- **Bird calls** contain strong high-frequency tonal components.
- **Traffic noise** is dominated by low-frequency energy and slower waveform variations.

These characteristics highlight how different sound sources exhibit unique spectral signatures.

---


