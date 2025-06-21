# EC7212 - Computer Vision and Image Processing  
## Take Home Assignment 1: Basic Image Processing Operations using OpenCV and NumPy

---

### Repository Overview

This repository contains Python implementations of fundamental image processing tasks as part of the EC7212 course assignment. The operations demonstrate core techniques including intensity level reduction, spatial averaging, image rotation, and block-wise spatial resolution reduction.

---

### Assignment Tasks

1. **Intensity Level Reduction:**  
   Reduce the number of intensity levels in an image from 256 to a variable number of levels, specified as integer powers of 2.

2. **Spatial Averaging:**  
   Perform simple spatial averaging on the image using neighborhood kernels of sizes 3×3, 10×10, and 20×20.

3. **Image Rotation:**  
   Rotate the image by 45 and 90 degrees.

4. **Block Averaging (Resolution Reduction):**  
   For every non-overlapping block (3×3, 5×5, and 7×7), replace the block pixels with their average value to simulate spatial resolution reduction.

---

### File Structure
``` bash
ec7212-image-processing-assignment1/
│
├── images/
│   └── input.png        # Your input image here
│
├── notebooks/
│   └── assignment1.ipynb  # Your Jupyter notebook with all code and outputs
│
└── README.md

```

---

### Usage Instructions

1. **Install required Python packages:**

```bash
pip install numpy opencv-python matplotlib

```

2. **Place your input image in the images/ folder and name it input.png.**

3. **Open the Jupyter Notebook:**

```bash

jupyter notebook notebooks/assignment1.ipynb
```
4. **Run all cells in the notebook to see the processing steps and visualize the results inline.**

5. **Processed images can be saved to disk directly from the notebook if desired.**
   

---


### Key Functions Implemented

- reduce_intensity_levels(image, n)
  Reduce grayscale intensity levels to n levels.

- spatial_average(image, kernel_size)
  Apply mean filtering (blurring) with a specified kernel size.

- rotate_image(image, angle)
  Rotate the image by a given angle.

- block_average(image, block_size)
  Replace each non-overlapping block with its average value.


---

## Sample Outputs

**The notebook displays visual results for:**

- Intensity level reductions at various levels (2, 4, 8, ..., 256)

- Spatial averaging with kernel sizes 3×3, 10×10, and 20×20

- Image rotations by 45° and 90°

- Block averaging for 3×3, 5×5, and 7×7 blocks


---

