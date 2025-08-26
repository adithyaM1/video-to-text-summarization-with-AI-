# AI Video Summarization

## Project Objective
Develop an AI-based system to automatically analyze video content, extract key moments, and generate concise summaries. The system includes a web interface for uploading videos and viewing summarized results.

## Features
- AI model for video summarization using PyTorch.
- Video processing utilities using OpenCV.
- Web server using Flask to handle video uploads and serve summarization results.
- Simple web frontend for video upload and summary display.

## Setup Instructions
1. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
2. Run the backend server:
   ```
   python backend/app.py
   ```
3. Open `frontend/index.html` in a web browser.

## Usage
- Upload a video file via the web interface.
- The backend processes the video and generates a summary.
- The summary is displayed on the web page.
