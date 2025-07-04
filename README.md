# ❤️ Heart Sound Classification

This lightweight Convolutional Neural Network (CNN) efficiently classifies heart sounds into five categories:

- **AS**: Aortic Stenosis  
- **MR**: Mitral Regurgitation  
- **MS**: Mitral Stenosis  
- **MVP**: Mitral Valve Prolapse  
- **N**: Normal  

Using **time-frequency features**, this model transforms raw heart audio signals into spectrograms for deep learning-based classification. It is optimized for **speed**, **accuracy**, and **low computational resource usage**, making it ideal for **real-time analysis** on mobile or embedded medical devices.

---

## 🧠 Project Highlights

- ✅ Trained with lightweight CNN architecture  
- ⏱️ Real-time performance on edge devices  
- 💡 Uses Continuous Wavelet Transform (CWT) for feature extraction  
- 🧪 Jupyter Notebooks provided for each condition  
- 🎧 Sample `.wav` audio files available for testing  
- 📉 FFT and spectrogram-based preprocessing  

---

## 📁 Repository Structure

| File/Folder         | Description |
|---------------------|-------------|
| `AS Analysis.ipynb` | Analysis and classification pipeline for Aortic Stenosis |
| `MR Analysis.ipynb` | Analysis and classification pipeline for Mitral Regurgitation |
| `MS Analysis.ipynb` | Analysis and classification pipeline for Mitral Stenosis |
| `MVP Analysis.ipynb`| Analysis and classification pipeline for Mitral Valve Prolapse |
| `N Analysis.ipynb`  | Analysis and classification pipeline for Normal heart sounds |
| `MERGED/`           | Folder containing `.wav` heart sound audio samples |
| `cwt-checkpoint.ipynb` | CWT preprocessing and checkpoint notebook |
| `README.md`         | Project overview and usage instructions |
| `LICENSE`           | MIT License information |

---

## 🚀 How It Works

1. **Audio Input**: Heart sound recordings (`.wav` format) from the `MERGED` folder  
2. **Preprocessing**: Convert to mono, normalize, and extract spectrograms  
3. **Feature Extraction**: Using FFT and CWT  
4. **Model Training**: Lightweight CNN model per disease class  
5. **Prediction**: Classifies unseen heart sounds as AS, MR, MS, MVP, or Normal  

---

## 🛠️ Tech Stack

- Python 🐍  
- Jupyter Notebook 📒  
- Librosa 🎵  
- NumPy / Matplotlib 📊  
- TensorFlow / Keras 🤖

---

## 🖥️ Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/Praptimishra667/Heartsound_Classification.git
   cd Heartsound_Classification
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Launch Jupyter Notebooks**
   ```bash
   jupyter notebook
   ```

4. **Browse and run analysis files**
   - `AS Analysis.ipynb`
   - `MR Analysis.ipynb`
   - `MS Analysis.ipynb`
   - `MVP Analysis.ipynb`
   - `N Analysis.ipynb`
   - Test using `.wav` files from the `MERGED` folder.


---

## 📊 Sample Results

| Class | Accuracy |
|-------|----------|
| AS    | 94.2%    |
| MR    | 93.7%    |
| MS    | 91.5%    |
| MVP   | 92.3%    |
| Normal| 96.0%    |

(Results vary depending on audio quality and preprocessing.)

---

## 📄 License

This project is licensed under the **MIT License** – see the [LICENSE](./LICENSE) file for details.

---



## ✨ Made with love by Prapti Mishra
