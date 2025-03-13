# 58-IVA-Assignment1-Part-B

---

## 🎯 Q1: Color Detection Project  

✅ **Goal:**  
Detect a specific color (red) using the HSV color space — a more reliable color model under different lighting conditions.  

✅ **Steps:**  
- Converts the image from **BGR** to **HSV** format.  
- Defines the color range for **red**.  
- Applies a **mask** to isolate red regions.  
- Displays the original and result images.  

✅ **Real-world Applications:**  
- Detecting objects of a specific color in robotics.  
- Traffic sign or product detection in factories.  

---

## 🔧 Q2: T-Pyramid Computation for Image Analysis  

✅ **Goal:**  
Generate a **T-Pyramid (Gaussian Pyramid)** — a multi-level, downscaled version of the original image.  

✅ **Steps:**  
- **Level 1:** Reduces the image by half.  
- **Level 2:** Further reduction for deeper analysis.  

✅ **Real-world Applications:**  
- Image compression and resizing.  
- Multi-scale feature detection in computer vision.  

---

## 🛠️ Q3: Image Smoothing Project  

✅ **Goal:**  
Apply different smoothing (blurring) filters to reduce noise while maintaining image structure.  

✅ **Steps:**  
- **Mean Blur:** Averages surrounding pixels (basic noise removal).  
- **Gaussian Blur:** Weighted average that preserves edges better.  
- **Median Blur:** Replaces each pixel with the median of its neighbors (best for salt-and-pepper noise).  

✅ **Real-world Applications:**  
- Noise reduction in medical or satellite images.  
- Preprocessing for edge detection or object recognition.  

---

## ✂️ Q4: Edge Detection using Sobel & Canny  

✅ **Goal:**  
Detect edges (boundaries) using two popular methods — **Sobel Operator** and **Canny Edge Detector**.  

✅ **Steps:**  
- **Sobel Operator:** Detects gradients in the X and Y directions.  
- **Canny Detector:** Applies noise reduction, gradient calculation, non-maximum suppression, and thresholding to find accurate edges.  

✅ **Real-world Applications:**  
- Object boundary detection in autonomous driving.  
- Feature extraction in image processing tasks.  

---

## 🔍 Q5: Object Detection with OpenCV (Face & Eye Detection)  

✅ **Goal:**  
Detect human faces and eyes using **OpenCV's Haar Cascade Classifiers**.  

✅ **Steps:**  
- Converts the image to **grayscale** for faster detection.  
- Detects **faces** first, then **eyes** within each face region.  
- Draws rectangles around detected faces and eyes.  

✅ **Real-world Applications:**  
- Face recognition systems (e.g., unlocking your phone).  
- Eye tracking in AR/VR environments.  

---

🚀 **Happy Coding!** 🔥  
