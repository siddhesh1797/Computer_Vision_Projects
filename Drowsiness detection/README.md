# Drowsiness Detection

- haarcascade files - It include haarcascade files to detect faces and eyes
- Drowsiness Detection - Main code
- alarm.wav - ringtone of alarm
- Trained model - To get click on [Link](https://drive.google.com/file/d/1U0L9eQ71i_Axj0KsEhTLE1SSKETKtR4I/view?usp=sharing)

**How it work**

**Step 1** – Take image as input from a camera.

**Step 2** – Detect the face in the image and create a Region of Interest (ROI).

**Step 3** – Detect the eyes from ROI and feed it to the classifier.

**Step 4** – Classifier will categorize whether eyes are open or closed.

**Step 5** – Calculate score to check whether the person is drowsy.
