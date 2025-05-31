# Football Analysis Project

## Introduction
The goal of this project is to detect and track players, referees, and footballs in a video using **YOLO**, one of the best AI object detection models available.  
We will also train the model to improve its performance.

Additionally, I assigned players to teams based on the colors of their t-shirts using **Kmeans** for pixel segmentation and clustering. With this information, we can measure a team's ball acquisition percentage in a match.

I also used **optical flow** to measure camera movement between frames, enabling myself to accurately measure a player's movement. Furthermore, I implemented **perspective transformation** to represent the scene's depth and perspective, allowing measure of player's movement in meters rather than pixels.

Finally, I calculated a player's **speed** and the **distance covered**.

---

## Screenshot
![Football Screenshot](https://github.com/Rudra116/Football-Match-Analysis-System/blob/main/football%20scrrenshot.png?raw=true)

---

## Modules Used
The following modules are used in this project:

- **YOLO**: AI object detection model
- **Kmeans**: Pixel segmentation and clustering to detect t-shirt color
- **Optical Flow**: Measure camera movement
- **Perspective Transformation**: Represent scene depth and perspective
- Speed and distance calculation per player

---

## Trained Models
- Trained **YOLOv5**

---

## Sample Video
👉 [Click here to watch the sample video](https://drive.google.com/file/d/1t6agoqggZKx6thamUuPAIdN_1zR9v9S_/view?usp=sharing)

---
## 📽️ Final Output Video
👉 [Click here to watch the output]([https://drive.google.com/file/d/YOUR_VIDEO_ID/view?usp=sharing](https://drive.google.com/file/d/1DuVggxMLfBiv4kuPjB0byvQMrz4KfcQ7/view?usp=sharing)

---

## Libraries Used
- Python 3.x
- `ultralytics`
- `supervision`
- OpenCV
- NumPy
- Matplotlib
- Pandas
- shutil
- os
- scikit-learn
