# 🛰️ Image Analysis using YOLOv8, EasyOCR, and OpenCV

This project processes and analyzes images using advanced computer vision techniques. It combines:

- ✅ **YOLOv8**: For detecting general objects.
- 🔤 **EasyOCR**: For recognizing text in images.
- ⚙️ **OpenCV**: For edge detection, grayscale conversion, and segmentation.

---

## 🧰 Features

- Object Detection using YOLOv8
- Optical Character Recognition using EasyOCR
- Edge Detection (Canny)
- Contour Segmentation
- Image Panel Visualization
- Outputs side-by-side analysis of each image

---

## 📂 Input Images

The following image files are analyzed:
- `gun.jpg`
- `TANK.jpg`
- `jet.webp`
- `grenade.jpg`
- `soldier.jpg`
- `tejas.jpg`

Place them in the same directory or update `IMAGE_PATHS` accordingly.

---

## 🛠️ Setup

### ✅ Prerequisites

Install the required libraries:

```bash
pip install torch torchvision ultralytics opencv-python easyocr matplotlib pillow
