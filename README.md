# EEG-WAYS-TO-DETECT-HAPPINESS
# EEG Ways to Detect Happiness

##  Project Overview
This project explores various methods to detect happiness using EEG (Electroencephalography) signals. By analyzing brainwave activity across different frequency bands, we aim to classify emotional states and identify EEG patterns associated with happiness.

##  Methodology
1. **Dataset:**
   - SEED-IV or other relevant EEG datasets.
   - EEG signals recorded across multiple channels.

2. **Preprocessing:**
   - Noise removal using filters.
   - Signal segmentation.
   - Feature extraction from different frequency bands (Delta, Theta, Alpha, Beta, Gamma).

3. **Feature Representation:**
   - Spectrogram-based transformation.
   - Spatial feature mapping (8x9 grid representation).

4. **Modeling:**
   - **Transfer Learning**: Inception V3 for feature extraction.
   - **Deep Learning**: CNN model for classification.
   - Comparison with traditional ML models (SVM, Random Forest, etc.).

## Results
- Model accuracy for classifying happiness vs. other emotions.
- Performance comparison of different feature extraction methods.
- Insights from EEG channel analysis.

## 🚀 How to Run
1. **Clone the Repository:**
   ```sh
   git clone https://github.com/SaiSrinivasa01/EEG-WAYS-TO-DETECT-HAPPINESS
   ```
2. **Install Dependencies:**
   ```sh
   pip install -r requirements.txt
   ```
3. **Run Preprocessing & Model Training:**
   ```sh
   python train_model.py
   ```

## 📜 References
- EEG-based emotion detection research papers.
- SEED-IV dataset documentation.


