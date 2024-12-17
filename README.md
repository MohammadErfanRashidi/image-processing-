# Image Manipulation with OpenCV and Matplotlib

This notebook demonstrates basic image manipulation techniques using OpenCV and Matplotlib libraries in Google Colab.

## Steps:

1. **Download an image:** An image of a dog is downloaded using `wget`.
2. **Import necessary libraries:** `matplotlib.image`, `matplotlib.pyplot`, `PIL`, and `cv2` are imported.
3. **Load and display the image:** The image is loaded using `mpimg.imread()` and displayed using `plt.imshow()`.
4. **Resize the image:** The image is resized using `PIL.Image.resize()` and saved as a new file.
5. **Convert to grayscale:** The image is converted to grayscale using `cv2.cvtColor()` and displayed using `cv2_imshow()`.
6. **Save the grayscale image:** The grayscale image is saved using `cv2.imwrite()`.

## Libraries Used:

- **OpenCV (cv2):** Used for image processing tasks, such as reading, writing, and converting images to grayscale.
- **Matplotlib:** Used for image display and visualization.
- **PIL (Pillow):** Used for image resizing and other manipulation tasks.

## Usage:

1. Open this notebook in Google Colab.
2. Run all the code cells in order.
3. Observe the outputs, including the original image, resized image, and grayscale image.
