Single-Leg Squat Analysis Using MediaPipe and Dynamic Time Warping

Project Demonstration

20-minute video presentation: 

Brief written summary: 

Project Overview

The main goal of this project is to develop a simple AI-based program that can analyze knee movement during a single-leg squat.

The program aims to calculate knee angles, estimate inward and outward knee deviation, and compare movement patterns between two squat videos. It also automatically classifies each squat as GOOD or BAD using a predefined 5-degree inward knee-deviation threshold.

This project was developed using Python in Google Colab and uses:

MediaPipe Pose Landmarker Lite for detecting human body joints

OpenCV for reading and processing videos

NumPy for calculating knee angles and deviation

Pandas for organizing and storing measurements

Matplotlib for creating graphs

Dynamic Time Warping (DTW) for comparing movement patterns


Methodology

Install the required Python libraries and download the pretrained MediaPipe model

Upload two front-facing single-leg squat videos into Google Colab

Use MediaPipe to detect the right hip, right knee, right ankle, and opposite hip

Calculate the projected knee angle using vector mathematics and the dot-product formula

Estimate inward and outward knee deviation using the hip–ankle reference line

Analyze every frame of both videos and record the knee measurements over time

Generate two graphs: Knee Angle vs. Time and Signed Knee Deviation vs. Time

Use Dynamic Time Warping (DTW) to compare movement patterns between the two squat videos

Classify each squat as GOOD or BAD 
