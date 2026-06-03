# License-Plate-Detection
# Russian License Plate Blurring using OpenCV

## Aim
To detect and blur Russian license plates from a car image using OpenCV and Haar Cascade Classifier.

## Technologies Used
- Python 3
- OpenCV
- NumPy
- Matplotlib

## Required Files

```bash
car_plate.jpg
haarcascade_licence_plate_rus_16stages.xml
Detection-Workshop.ipynb
```

## Procedure

1. Import the required libraries such as OpenCV, NumPy, and Matplotlib.
2. Read the input car image using OpenCV.
3. Create a display function for proper image visualization.
4. Load the Haar Cascade XML classifier for Russian license plate detection.
5. Detect the license plate region using `detectMultiScale()`.
6. Extract the detected license plate region (ROI).
7. Apply median blur to the detected plate region.
8. Replace the original license plate with the blurred region.
9. Display the final blurred output image.

## Output

<img width="766" height="433" alt="image" src="https://github.com/user-attachments/assets/967abd2d-e51c-406c-80a4-04f61c5d19fb" />

<img width="770" height="433" alt="image" src="https://github.com/user-attachments/assets/cd7d77dd-5b62-49f2-8777-db6b5a1b0c2d" />

## Result

Thus, Russian license plate detection and blurring were successfully implemented using OpenCV and Haar Cascade Classifier. The detected license plate region was automatically blurred for privacy protection.
