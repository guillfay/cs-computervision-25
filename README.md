# cs-computervision-25
Computer Vision Labs — CentraleSupélec 2025



# Computer Vision Labs — CentraleSupélec 2025

Practical labs from the Computer Vision course at CentraleSupélec. Each notebook explores a core CV topic through implementation and experiments.

---

## Labs

### Image Colorization
Automatic colorization of grayscale images. Explores learning-based approaches to predict plausible color from luminance information, framing colorization as a regression or classification problem in LAB color space.

### Motion & Optical Flow
Estimation of pixel-level motion between consecutive video frames. Covers classical methods (Lucas-Kanade, Horn-Schunck) and their applications to motion analysis and object tracking.

### Video Magnification
Amplification of subtle, imperceptible motions in video — such as pulse-induced skin color changes or micro-vibrations. Based on Eulerian video magnification, which operates in the frequency domain on decomposed spatial pyramids.

---

## Structure

```
image_colorization.ipynb
motion_and_optical_flow.ipynb
video_magnification.ipynb
```

## Requirements

```bash
pip install numpy opencv-python matplotlib scikit-image torch torchvision
```