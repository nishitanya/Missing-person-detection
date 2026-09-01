# Missing & Deceased Person Detection System

## Overview

The Missing & Deceased Person Detection System is an AI-based application designed to assist in identifying missing and unidentified individuals using computer vision and machine learning.

The system provides a web-based interface where users can interact with the application, submit information, and use image-based identification functionality.

## Key Features

- Missing person identification
- Unidentified person detection
- Face-based image matching
- Image upload and processing
- Person information management
- Separate machine learning services for different detection tasks
- Web-based application interface
- Location and geocoding utilities
- Backend API integration

## Project Structure

```text
Missing-person-detection/
│
├── Hack4Safety/
│   ├── app/
│   ├── components/
│   ├── public/
│   ├── utils/
│   ├── package.json
│   ├── package-lock.json
│   ├── next.config.ts
│   └── tsconfig.json
│
├── mlModel/
│   ├── app.py
│   ├── Dockerfile
│   └── requirements.txt
│
├── mlModelfall/
│   ├── app.py
│   ├── Dockerfile
│   └── requirements.txt
│
└── README.md
