# 🎨 QuickDraw AI Camera

An interactive computer vision application that allows you to draw in the air using a colored object and a webcam. A real-time neural network then tries to guess what you drew! This project is inspired by Google's [Quick, Draw!](https://quickdraw.withgoogle.com/) game.


***

## Features

* **Real-Time Object Tracking**: Tracks a colored object (red, green, or blue) using your webcam.
* **Live Drawing**: Translates the object's movement into a digital drawing on a canvas.
* **AI-Powered Recognition**: Uses a pre-trained PyTorch model to classify your drawing.
* **Interactive Interface**: Simple keyboard controls to start, stop, and clear drawings.
* **Customizable**: Command-line arguments to change the tracking color, canvas visibility, and more.

***

## 🛠️ Tech Stack

* **Python 3**
* **OpenCV**: For all computer vision tasks, including camera access, image processing, and color tracking.
* **PyTorch**: For loading the pre-trained deep learning model and performing image classification.
* **NumPy**: For efficient numerical operations and image manipulation.

***

## 🚀 Setup and Installation

Follow these steps to get the project running on your local machine.

### **1. Prerequisites**

Make sure you have **Python 3.8+** and **pip** installed.

### **2. Clone the Repository**

```bash
git clone https://github.com/abhiruchipb/QuickDraw
cd QuickDraw
