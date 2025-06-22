# Audio to Text

This repository contains a basic speech-to-text conversion tool built using Python. The project was developed during my university coursework and is intended solely for learning and academic purposes.

## Overview

The notebook demonstrates the use of Python libraries to convert spoken audio into written text. It captures live audio from a microphone and uses speech recognition to generate corresponding textual output.

## Features

- Live audio recording through microphone input  
- Real-time speech-to-text conversion  
- Basic error handling for inaudible or unclear inputs  

## Technologies Used

- Python 3  
- Jupyter Notebook  
- `speech_recognition`  
- `pyaudio`  

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/udita2404/audio-to-text.git
cd audio-to-text
```

### Install Dependencies

Ensure you have Python 3 installed, then install the required libraries:

```bash
pip install SpeechRecognition pyaudio
```

> **Note**: Installing `pyaudio` may require additional system-specific setup (especially on Windows or macOS). Refer to official documentation if you face installation issues.

### Run the Notebook

Launch the notebook using:

```bash
jupyter notebook
```

Open the notebook file and follow the steps inside to begin audio capture and transcription.

## Limitations

- Designed for English language input  
- Requires a functional microphone and permission to access it  
- Best performance in quiet environments  

## Purpose

This project was created as a part of academic learning and is not intended for production or commercial use.
