# Kystverket AI — Summer Internship 2023

This repository contains work done by summer interns at the TEFT Lab in Ålesund for [Kystverket](https://www.kystverket.no/). The overall goal is to support Kystverket's digital twin application by automatically extracting building attributes from image data using computer vision.

A full write-up of the project background, findings, and recommendations for the way forward is available in the [project report](Teft-summer-intership-project-report.pdf).

## Sub-projects

### [building-colors](building-colors/readme.md)
Automatic classification of building facade colors using the YOLO object detection algorithm and Google Maps imagery. The system fetches street-level images of buildings by address, runs a trained YOLO model to detect and classify building colors, and exports the results. Intended as a proof of concept for enriching the digital twin with realistic building appearance.

### [python-image-detection](python-image-detection/README.md)
A general-purpose template for training and running YOLO (YOLOv8) image detection models in Python. Provides a simplified `Detector` wrapper around Ultralytics YOLO, example notebooks, and a guide for creating custom datasets with Roboflow. Acts as the underlying detection framework used by the building-colors project.

## Contact

- **Elias Lerheim Birkeland** — eliaslbi@stud.ntnu.no
- **Martin Valderhaug Larsen** — martivl@stud.ntnu.no
- **Simon Lervåg Breivik** — simonlb@ntnu.no
