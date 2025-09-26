## YOLO Real Time Object Detection

This project implements a real time object detection via video, webcam and image detection using YOLO algorithm. YOLO is a object detection algorithm which stand for You Only Look Once. I've implemented the algorithm from scratch in Python using pre-trained weights.Real time detection can be use via command prompt or GUI.

<table>
  <tbody>
	<tr align="center">
		<th><strong>Real-Time Road Detection-1</strong></th>
	</tr>
	<tr align="center">
		<td><img src="https://github.com/muhammadshiraz/YOLO-Real-Time-Object-Detection/blob/master/doc/detector1.gif"></td>		
	</tr>
	<tr align="center">
		<th><strong>Real-Time Road Detection-2</strong></th>
	</tr>
	<tr align="center">
		<td><img src="https://github.com/muhammadshiraz/YOLO-Real-Time-Object-Detection/blob/master/doc/detector2.gif"></td>
	</tr>
	<tr align="center">
		<th><strong>A Real-Time Webcam Detection</strong></th>
	</tr>
	<tr align="center">
		<td style="width: 100%;"><img src="https://github.com/muhammadshiraz/YOLO-Real-Time-Object-Detection/blob/master/doc/webcam_detector.jpg"></td>
	</tr>
</tbody>
</table>

Yolo is a deep learning algorythm which came out on may 2016 and it became quickly so popular because it’s so fast compared with the previous deep learning algorythm.
With yolo we can detect real time objects at a relatively high speed. With a GPU we would be able to process over 45 frames/second while with a CPU around a frame per second.

OpenCV dnn module supports running inference on pre-trained deep learning models from popular frameworks like Caffe, Torch and TensorFlow.



# YOLO Real-Time Object Detection

This project implements **real-time object detection** via video, webcam, and image detection using the **YOLO (You Only Look Once)** algorithm. Implemented in Python using pre-trained weights. Real-time detection can be run via **Command Prompt** or **GUI**.

---

## Features
- Real-time object detection on images, videos, and webcam feed.
- High-speed detection using YOLO algorithm.
- Supports GPU and CPU inference (GPU: ~45 FPS, CPU: ~1 FPS).

---

## Demo

### Real-Time Road Detection
![Real-Time Road Detection-1](images/detector1.gif)  
![Real-Time Road Detection-2](images/detector2.gif)  

### Webcam Detection
![Real-Time Webcam Detection](images/webcam.gif)

---

## About YOLO
YOLO is a deep learning object detection algorithm introduced in **May 2016**. It became popular due to its **high speed** compared with previous detection algorithms. YOLO detects objects in real-time with high accuracy.

OpenCV `dnn` module is used to run inference on pre-trained models from popular frameworks like Caffe, Torch, and TensorFlow.

---

## Requirements
- Python 3.6+
- OpenCV 4.2.0
- gradio
- NumPy (optional)
- Other dependencies listed in `requirements.txt`

---

## Installation
1. Clone the repository:
```bash
git clone https://github.com/NAGARAJU4582/YOLO-RealTime-Object-Detection.git

## Requirement
<ul>
<li>gradio</li>	
<li>OpenCV 4.2.0</li>
<li>Python 3.6</li>
</ul>
