# Facial Emotion Detection (Colab)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1ACbeuXle-Cf-05_5xGzEwWwlHlgu0wcc#scrollTo=PHO3XrmFFyIT)

A Google Colab notebook that detects human emotions from face images. Runs end-to-end in the browser—no local setup.

---

## What this repo is
- ✅ A single Colab notebook you can open and run
- 🧠 Trains/evaluates a model for facial emotion recognition
- 📈 Produces metrics/plots and sample predictions
- 💾 Can read/write from Google Drive for datasets and outputs

---

## Quick start (Colab)
1. Click the **Open in Colab** badge above.
2. In Colab, go to **Runtime → Run all**.
3. If prompted, **connect Google Drive** (for data + saving outputs).
4. Follow the on-screen cell instructions (set paths, run inference).


---

## Using your own data
It has many options:
- **Drive dataset**: Put images in `MyDrive/datasets/emotions/` and set `DATA_DIR` to that path.
- **Upload a few images**: Use the upload cell in Colab to test quickly.
- **Webcam (if included)**: Run the webcam cell to test live predictions.

> Common class labels: `angry, disgust, fear, happy, sad, surprise, neutral` (your notebook may vary).

---

## Typical workflow
1. **Preprocess**: Resize/normalize faces (handled in the notebook).
2. **Train**: Start training; watch loss/accuracy logs.
3. **Evaluate**: View accuracy/F1/confusion matrix.
4. **Predict**: Run on sample images or webcam frames.
5. **Export**: Save the model and plots to `OUTPUT_DIR`.

---

## Results (fill these in after a good run)
- Val Accuracy: `XX.X%`
- Best epoch: `N`
- Notes: `e.g., better with grayscale + data augmentation`
- Sample predictions: see `assets/` or notebook output

