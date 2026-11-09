# Cephalometric Landmark Analysis

A Cairo University team project that uses deep learning to locate anatomical landmarks on lateral cephalometric X-rays. The PyQt application overlays predictions and, for images with reference annotations, displays both sets of landmarks for visual comparison.

![Example showing predicted landmarks in blue and reference landmarks in green](https://user-images.githubusercontent.com/61363974/210420038-c79c2e1a-dcc0-4e16-ac71-ae8723c13904.png)

## What the application shows

- A user selects an X-ray and chooses a model. The project compared DenseNet and EfficientNet approaches to predict 19 landmark coordinates.
- The interface overlays the predicted points, can show the reference labels when available, and saves an annotated image.
- The [main script](main.py) handles inference and image export. The [GUI layout](gui.py) defines the controls, and the [model reference](Models/Models%20Drive%20Link.txt) points to the separately stored weights.

## Contributors

- Mohammed Mostafa Nezar
- Ahmed Mostafa Mohamed
- Ahmed Hatem Farouk
- Ahmed Hossam Aldeen
- Abdullah Mohammed Shazli
- Abdulkhalek Abdulmalek Al-fakih
- Zeyad Ayman
- Ahmed Gamal
- Omar Essam Mohamed
