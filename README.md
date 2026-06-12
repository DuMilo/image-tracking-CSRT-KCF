# Image Tracking Project: CSRT and KCF Algorithms

## Project Description
This project focuses on developing robust object tracking solutions using CSRT (Correlation Filters with Weighted Convolution Responses) and KCF (Kernelized Correlation Filters) algorithms. The objective is to implement and compare different computer vision tracking methodologies to effectively track and follow objects in video sequences with high accuracy and efficiency.

## Objectives
- To build efficient tracking models using CSRT and KCF algorithms for real-time object tracking.
- To explore and compare different tracking architectures and optimization strategies to improve tracking accuracy and robustness.
- To provide a user-friendly interface for inputting video sequences or camera feeds for object tracking.
- To evaluate and measure tracking performance using standard metrics and visualizations.

## Features
- Real-time object tracking in video sequences
- Support for multiple tracking algorithms (CSRT and KCF)
- Video input and camera feed support
- Bounding box visualization with tracking information
- Performance metrics reporting (tracking accuracy, frame processing speed)
- Support for various video formats (MP4, AVI, MOV)

## Technologies Used
- Python
- OpenCV for computer vision and tracking algorithms
- NumPy for numerical computations
- Git for version control
- Jupyter Notebook for experimentation

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/DuMilo/image-tracking-CSRT-KCF.git
   cd image-tracking-CSRT-KCF
   ```
2. Create a virtual environment and activate it:
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Prepare your video file or use a camera feed
2. Run the tracking script with your preferred algorithm:
   ```bash
   python track_csrt.py --video input_video.mp4
   ```
   or
   ```bash
   python track_kcf.py --video input_video.mp4
   ```
3. View the results with bounding boxes and tracking metrics

## Project Structure
- `track_csrt.py` - CSRT tracking implementation
- `track_kcf.py` - KCF tracking implementation
- `utils.py` - Helper functions for video processing and visualization
- `requirements.txt` - Project dependencies
- `notebooks/` - Jupyter notebooks for experimentation
