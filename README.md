 # EEG-WAYS-TO-DETECT-HAPPINESS

##  Project Overview
This project explores various methods to detect happiness using EEG (Electroencephalography) signals. By analyzing brainwave activity across different frequency bands, we aim to classify emotional states and identify EEG patterns associated with happiness.

##  Methodology
1. **Dataset:**
   - SEED-IV or other relevant EEG datasets.
   - EEG signals recorded across multiple channels.
   - SJTU Emotion EEG Dataset for Four Emotions (SEED-IV) This is a subset of SEED (SJTU Emotion EEG Dataset: https://bcmi.sjtu.edu.cn/~seed/

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

##  How to Run
1. **Clone the Repository:**
   
   git clone <- https://saisrinivasa01.github.io/EEG-WAYS-TO-DETECT-HAPPINESS/ ->

##  References
- EEG-based emotion detection research papers.
- SEED-IV dataset documentation.


