# Image Processing Exercise

## 1. Exercise Overview (55 Marks)  
The following tasks involve image processing techniques using OpenCV and related libraries. Each sub-task carries a specified weightage, contributing to a total of 55 marks.

---

### 1.1 Image Enhancement (20 Marks)  
Perform enhancement of the image using the following techniques:  
1. **Histogram Equalization**: Redistribute pixel intensities to enhance contrast.  
2. **Sharpening**: Enhance edges and details in the image.  
3. **Color Balance**: Correct color cast in the image.  
4. **Noise Reduction**: Remove noise for a clearer image.  

---

### 1.2 Edge Detection (10 Marks)  
Perform edge detection using:  
1. **Gradient Filtering using Sobel Operator**: Apply Sobel filters in both x and y directions to detect gradients.  
2. **Laplacian-based Edge Detection**: Apply the Laplacian operator and convert absolute values of the Laplacian.  

---

### 1.3 Noise Removal Using Arithmetic Filtering (5 Marks)  
Steps to remove noise:  
1. Load the noisy image.  
2. Apply **Arithmetic Mean Filter** with kernel sizes of 3 and 5.  
3. Finalize and display the filtered image.  

---

### 1.4 Adding Noise with Salt & Pepper (5 Marks)  
Steps to add salt-and-pepper noise:  
1. Load the clean image.  
2. Apply noise with a density of **0.05** and **0.07**.  
3. Select random pixels and add noise.  
4. Finalize and display the noised image.  

---

### 1.5 Image Compression (10 Marks)  
Compress the image using the following libraries:  
1. **Pillow**: Perform compression and save the image in a reduced size.  
2. **OpenCV**: Compress the image and analyze the size reduction.  

---

### 1.6 Image Filtering (15 Marks)  
Apply the following filtering techniques:  
1. **Gaussian Blurring**: Use a kernel size of **(5, 5)** to blur the image.  
2. **Median Filtering**: Apply a **median filter** with a kernel size of 5.  
3. **Bilateral Filtering**: Use a **diameter of 9**, **color = 75**, and **space = 75** for filtering.  

---
