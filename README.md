
# WASD: Wireless Anomaly Signal Dataset

## Overview

WASD (Wireless Anomaly Signal Dataset) is designed for anomaly signal detection in wireless signals within fixed urban scenarios. It combines real-world signals measured across 19 LTE and 5G bands with simulated anomalous signals. This dataset is suitable for training various object detection networks and developing robust deep learning models for accurate and efficient anomaly detection in real-world environments.

## Paper Link
Under Review

## Dataset Features

* **Real-world Measurement Data**: Includes real-world signal data collected from 19 LTE and 5G bands.
* **Diverse Anomaly Signals**: Contains various types of simulated anomaly signals, including tone, chirp, and pulse signals.
* **Realistic Simulation**: Employs realistically feasible random-based parameters and configured fading channels in accordance with 3GPP standards to simulate real-world conditions.
* **Large-scale Dataset**: A comprehensive dataset comprising 85,500 samples across 19 bands.
* **Versatile Usage**: Includes both object detection and normal data, suitable for both supervised and unsupervised learning approaches.

## Dataset Structure

* **IQ Data**: Raw IQ data (`.bin` and `.json` files) measured for each band.
* **Spectrogram Data**: Spectrogram data (`.npy` files) generated using Short Time Fourier Transform (STFT).
* **Labels**: Label data (`.csv` files) containing bounding box coordinates and Interference-to-Signal Ratio (ISR) information of anomaly signals.
* **Data Loaders**: Example code for loading the IQ data, spectrogram datas into python workspaces.
* **Anomaly Signal Generation Examples**: Example code for generating abnormal wireless signal (tone, chirp, pulse) with the fading model. The detailed information can be found in the paper.

## Dataset Access

* **Total Size**: 784.24 (GB)
The download link will be available soon.
Since the data amount is large to deal with one file, the compressed file will be delivered as chunks.

* **Chunk 1**
* **Chunk 2**
* **Chunk 3**
* **Chunk 4**
* **Chunk 5**
* **Chunk 6**
* **Chunk 7**
* **Chunk 8**
* **Chunk 9**
* **Chunk 10**
* **Chunk 11**
* **Chunk 12**
* **Chunk 13**
* **Chunk 14**
* **Chunk 15**
* **Chunk 16**
* **Chunk 17**

## Authors
Jinha Kim (jinha.kim@o.cnu.ac.kr), Hyeongwoo Kim (Hyeongwoo.kim@o.cnu.ac.kr), Byungkwan Kim(byungkwan.kim@cnu.ac.kr)

## Acknowledgements
This work was supported by the MSIT/IITP through the ICT R&D program (RS-2023-00229541).
