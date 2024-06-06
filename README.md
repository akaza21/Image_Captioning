# Image Captioning Project

##Introduction
This Flask application delivers an image captioning service that utilizes a sophisticated deep learning model developed as part of a final year project. The model employs the CLIP encoder coupled with a Transformer-based decoder to generate contextually relevant and accurate captions for images. This solution showcases the integration of cutting-edge AI technologies for practical applications.

## Features

User-friendly web interface for submitting image URLs.
Utilizes a custom-developed AI model combining CLIP and Transformer technologies for caption generation.
Supports a wide range of image inputs via URL.

## Technologies

- Python 3
- Flask
- PyTorch
- CLIP (Contrastive Language–Image Pre-training)
- Transformers


## Prerequisites
Ensure you have Python and Pip installed on your machine. It is also recommended to manage Python packages in a virtual environment.

## Installation
Clone the Repository

```bash
git clone https://github.com/yourusername/flask-image-captioning.git
cd flask-image-captioning
```
## Set Up a Virtual Environment (Optional)

For Windows:

```bash
python -m venv env
.\env\Scripts\activate
```
For macOS and Linux:

```bash
python3 -m venv env
source env/bin/activate
```
##Install Dependencies

```bash
pip install -r requirements.txt
```

## Configuration

Create a .env file in the root directory and add necessary configurations such as model parameters and API keys, if required.

- Running Locally
-Start the Flask Server

```bash
python app.py
```
- Access the Application

Open your web browser and visit http://127.0.0.1:8080. You should see the web interface of the image captioning service.

## Model Overview

The captioning model integrates the CLIP encoder with a Transformer decoder. CLIP (Contrastive Language–Image Pre-training) encodes the image into a feature vector that effectively captures visual information. This vector is then processed by a Transformer-based decoder, renowned for its effectiveness in handling sequence data, to generate descriptive captions. This combination allows for generating highly accurate and contextually relevant captions for a wide array of images.

## Usage

To caption an image:

- Navigate to the web interface.
- Paste the URL of the image into the input field.
- Click the 'Generate' button to display the generated caption.
