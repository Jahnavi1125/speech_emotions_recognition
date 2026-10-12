# Speech Emotion Recognition

Classifies speech audio into eight emotions using Mel-spectrograms and a CNN.

**Tech:** Python, TensorFlow/Keras, Librosa, NumPy, Matplotlib

## Dataset
RAVDESS (Ryerson Audio-Visual Database of Emotional Speech and Song). Download it separately and place it in the folder the notebook expects.

## Approach
1. Load audio files and extract Mel-spectrograms
2. Apply data augmentation
3. Train a CNN with TensorFlow/Keras to classify 8 emotions
4. Evaluate with test accuracy and a confusion matrix_

## How to Run
```bash
pip install tensorflow librosa numpy matplotlib scikit-learn
```
Open the notebook in Jupyter and run the cells in order.

## Future Improvements
- Try CRNN or transformer-based audio models
- Test on additional emotion datasets
