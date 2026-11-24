# Experiment 01: Image to Grayscale

**Aim:** Perform basic image handling and processing operations by reading an image in Python and converting it to grayscale.

## Software requirements
- Python 3.9 or later
- OpenCV and NumPy (see `requirements.txt`)


## Algorithm
1. Load the sample input from this experiment's local `input/` folder.
2. Validate that the image/video was loaded successfully.
3. Apply the OpenCV operation for this experiment.
4. Save the processed result and a side-by-side output preview in `screenshots/`.

## Procedure
1. Open a terminal in this folder.
2. Install dependencies: `python -m pip install -r requirements.txt`.
3. Run: `python experiment.py`.
4. For image experiments, replace `input/sample.jpg` with your own image (keep the same filename). For video experiments, replace `input/sample.mp4`.
5. Optional: use `python experiment.py --show` to open display windows on a desktop.

## Sample input
- `input/sample.jpg` (included with this experiment).

## Expected output
A processed image or video is saved locally. Image experiments save `screenshots/processed_output.png` and `screenshots/output_preview.png`. Video experiments save an output preview; reverse-video experiments also create a video file in this folder. Exact detection results depend on the input content.

## Source code
- `experiment.py`

## Execution command
```bash
python -m pip install -r requirements.txt
python experiment.py
```

## Screenshots
- [Output preview](screenshots/output_preview.png)
- [Processed output](screenshots/processed_output.png)


## Notes
- This folder is self-contained and does not import code or data from another experiment.
- Face/eye/smile cascades are supplied by the installed OpenCV package. Use images you have permission to process.
- Experiment 25 uses classical contour/shape candidate localization, not a trained watch classifier. Experiment 28 marks moving regions using background subtraction, not a trained vehicle classifier.
