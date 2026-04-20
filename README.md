# 🎨 AR Drawing Pad – OpenCV Real-Time Virtual Sketch System

This project is a real-time **Augmented Reality Drawing Application** built using OpenCV. It allows users to draw on the screen using colored objects (like markers) detected via webcam, simulating a virtual pen experience.

The system detects predefined colors (Green, Red, Blue) in real-time using HSV color space segmentation and tracks their movement to draw smooth lines on a virtual canvas. It also includes a simple UI overlay for color switching and canvas control.

## 🚀 Features

* Real-time color detection using HSV filtering
* Virtual drawing using object tracking
* Multi-color support (Green / Red / Blue)
* On-screen UI buttons for interaction
* Clear canvas functionality
* Live mask visualization for debugging
* Smooth line drawing using contour tracking

## 🛠️ Tech Stack

* Python
* OpenCV
* NumPy

## 🎯 How It Works

1. The webcam captures live video feed
2. The system detects a specific color object in HSV space
3. The object’s movement is tracked frame-by-frame
4. A virtual line is drawn following the object trajectory
5. Users can switch colors or clear the canvas using controls

## 💡 Use Cases

* Interactive AR applications
* Computer vision learning project
* Gesture-based drawing systems
* Educational demo for object tracking and segmentation

## 📌 Controls

* `G` → Green pen
* `R` → Red pen
* `B` → Blue pen
* `C` → Clear canvas
* `ESC` → Exit

