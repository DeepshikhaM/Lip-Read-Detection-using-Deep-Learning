# Lip-Read-Detection-using-Deep-Learning
A deep learning-based model that accurately predicts spoken sentences from silent video sequences, enabling speech recognition without audio for accessibility and security applications.

# 🗣️ Lip Read Detection Using Deep Learning

## 📌 Project Overview
This project implements **LipNet**, a deep learning-based lip-reading model that predicts spoken sentences from video sequences. It enables speech recognition using only visual information, making it useful in noisy environments and for accessibility applications.

## 🎯 Objectives
- Develop an **end-to-end deep learning model** for **lip-reading**.
- Enhance speech recognition accuracy without relying on audio.
- Improve accessibility for individuals with **hearing impairments**.
- Explore real-time applications in **security, healthcare, and human-computer interaction**.

## 📂 Dataset Used
- **GRID Corpus**: A publicly available dataset containing **audio-visual speech recordings**.
- Includes **34 speakers** with **1000 spoken sentences each**.
- The dataset provides **word-level transcriptions** aligned with video frames.

## 🔄 Data Preprocessing
- **Frame Extraction**: Converts videos to sequences of frames.
- **Grayscale Conversion**: Reduces computational complexity.
- **GIF Format Processing**: Converts frame sequences into GIFs for sequential processing.
- **Text Alignment**: Maps speech transcriptions to video frames.

## 🏗 Model Architecture
The model follows a deep learning **sequence-to-sequence** approach:
- **3D Convolutional Layers (Conv3D)** for feature extraction.
- **Bidirectional LSTM** for temporal sequence modeling.
- **Dense Layers** for classification.
- **Connectionist Temporal Classification (CTC) Loss** for sequence alignment.

## ⚙️ Training & Optimization
- Trained using **Adam optimizer** with **learning rate scheduling**.
- **Data augmentation** applied to improve generalization.
- **Model checkpointing** ensures training efficiency.

## 📊 Performance & Results

- Evaluated using **word accuracy** and **sentence reconstruction quality**.
- Achieves **high accuracy** in predicting spoken sentences.
- Effective in **noisy environments** where traditional speech recognition fails.

## 🔬 Future Enhancements
- **Real-time lip reading** for accessibility applications.
- **Integration with voice assistants** to improve recognition accuracy.
- **Security applications** for speaker verification.
- **Sign language integration** for better communication tools.

## 📌 References
- **LipNet Paper:** Assael et al. (2016) - *End-to-End Sentence-level Lipreading*.
- **GRID Corpus:** Cooke et al. (2006) - *A Multitalker Audiovisual Sentence Corpus*.

---


