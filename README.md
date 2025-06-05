# 🎵 Pitch Detection and Gender Classification Using Audio Signal Analysis

This project is a **Digital Signal Processing (DSP)** application developed in Python to detect **pitch** (fundamental frequency) from a voice recording and classify the **speaker's gender** based on pitch estimation. It also provides visual insights into the time-domain signal, autocorrelation, and frequency spectrum.

---

## 📌 Features

- Load and analyze `.wav` audio files.
- Perform **autocorrelation** to estimate pitch.
- Classify **gender** based on detected pitch range.
- Display:
  - Time-domain waveform
  - Autocorrelation graph
  - Frequency spectrum (FFT)
- Play back the audio signal.

---

## 🧠 How It Works

1. **Load Audio**  
   Audio is loaded using `librosa`, preserving its original sampling rate.

2. **Pitch Estimation**  
   - Uses **autocorrelation** to find periodicity.
   - Calculates pitch using:  
     Pitch = Sampling Rate / Period in Samples

3. **Gender Classification**  
   Based on known pitch ranges:
   - Male: 85–180 Hz  
   - Female: 165–255 Hz

4. **FFT Analysis**  
   Fast Fourier Transform is used to analyze the frequency content.

---

## 📊 Visualization Output

- **Waveform** of the audio
- **Autocorrelation** plot with peak indicating estimated pitch
- **Frequency Spectrum** (FFT plot)

---

## 📂 Files

- `pitch_detection_and_gender_classification.ipynb` – Main Python script for pitch detection and gender classification  
- `female_voice.wav` / `male_voice.wav` – Sample audio files (replace with your own)  
- `README.md` – Project overview and explanation

---

## 📚 Applications

- Voice-controlled systems  
- Speech recognition preprocessing  
- Speaker identification systems  
- Forensic audio analysis  
- Gender-based speech filtering

---

## ✅ Conclusion

This project showcases how **core digital signal processing techniques** like **autocorrelation** and **FFT** can be effectively applied to real-world problems such as **pitch detection** and **gender classification**. It demonstrates the value of signal analysis in extracting meaningful features from audio and forms a solid base for advanced audio processing systems like voice assistants, biometric authentication, and smart communication tools.

---
