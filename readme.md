# Background Generation with Diffusion Model Inpainting

This project implements a background generation system using a diffusion-based inpainting model. It allows users to upload images and generate new backgrounds by modifying the original image's background while preserving the foreground. This is particularly useful for creating new scenes or adjusting backgrounds while maintaining the integrity of the main subject.

## Features
- Background removal using a mask.
- Background regeneration with diffusion inpainting.
- Adjustable inpainting parameters for fine-tuning the results.

## Demo
A live demo is available at: [HuggingFace Space](https://huggingface.co/spaces/akashmaurya/bg_generator)

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Technical Details](#technical-details)
- [Deployment Instructions](#deployment-instructions)
- [Challenges Faced](#challenges-faced)
- [License](#license)

---

## Installation

### Prerequisites
- Python 3.8 or higher
- [Streamlit](https://streamlit.io/) for the web UI
- Other required libraries: 
  - `torch`
  - `diffusers`
  - `opencv-python`
  - `Pillow`

#### Clone the Repository
```
git clone https://github.com/JrMlMaurya/3EYE.git
cd 3EYE
```

You can install the required libraries using `pip`:

```
pip install -r requirements.txt
```

Run the 'app.py' file using `streamlit`:

``` streamlit run app.py```

## Usages

- Upload any image and get the background generated based on the prompt









