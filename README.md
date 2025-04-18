# White-Line-Detection-with-OpenCV-and-Python
A real-time white lane detection project using OpenCV, designed to isolate road lines while filtering out noise like sky, shadows, and guardrails.

# White Lane Detection using OpenCV

This project demonstrates real-time white lane detection on road videos using Python and OpenCV. It uses color filtering, region of interest masking, Canny edge detection, and Hough Line Transform to isolate **white lane lines** while minimizing false detections from the sky, shadows, and railings.

---

## 🎯 Project Objective

- Detect **only the white lane lines** on the road
- Filter out irrelevant regions like sky, buildings, shadows, and side rails
- Provide a clean output using real-time video processing

---

## 🧠 Key Features

- ✅ HSV color filtering for white color
- ✅ Region of Interest (ROI) masking to focus on road area
- ✅ Canny edge detection for highlighting contours
- ✅ Hough Line Transform to detect straight lines
- ✅ Real-time video processing with frame-by-frame detection

---

## 🔧 Tech Stack

- **Language:** Python
- **Libraries:** OpenCV, NumPy
- **Input:** Road driving footage (`.mp4`)
- **Output:** Green-highlighted white lane lines over video

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/chamo111/white-line-detection.git
   cd white-line-detection

