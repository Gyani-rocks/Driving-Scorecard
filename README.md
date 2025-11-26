# Driving-Scorecard
AI-powered Driving Scorecard System (Lane Detection, Speed Estimation, Tailgating, Overtaking, Hard Braking, and Report Generation)
This project analyzes dashcam or driving footage and automatically generates a professional driving safety report using computer vision and machine learning.
It detects:

✔ Lane departures
✔ Tailgating
✔ Overtaking
✔ Hard braking events
✔ Approximate speed
✔ Distance from lane center
✔ Unsafe driving patterns
✔ Final safety score
✔ PDF / HTML reports with images

Developed as part of a college ML/AI project.

🧠 Features
1️⃣ Frame Extraction
Converts uploaded video into individual frames
Uses OpenCV
2️⃣ Lane Detection & Lane Offset
Detects lane markers
Computes distance from center
Flags lane departures
3️⃣ Tailgating Detection
Uses YOLO to detect vehicles
Measures relative size (height ratio)
Flags unsafe following distances
4️⃣ Overtaking Detection
Tracks multiple vehicles using bounding boxes
Detects if ego-vehicle passes another
Saves evidence images
5️⃣ Hard Braking
Analyzes bounding box growth rate
Large negative speed difference indicates harsh braking
6️⃣ Event Merging
All results combined into final events.
7️⃣ PDF / HTML Report Generation
Two types of reports:
A. Full Detailed Report
B. Short, Professional, Panel-Ready Report
