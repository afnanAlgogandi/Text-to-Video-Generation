# Text-to-Video-Generation
This code takes an Arabic text description as input, translates it to English using Google Translate, and generates a video sequence that matches the translated text description. It utilizes a pre-trained model and diffusion techniques to create the video content.


This README provides an overview and usage instructions for the code that demonstrates text-to-video generation using a pre-trained model. The code uses Python and several libraries to translate text from Arabic to English and generate a video sequence based on the translated text.

## Prerequisites

Before running the code, ensure you have the following libraries installed:
- `torch`: PyTorch library
- `diffusers`: A library for diffusion models
- `moviepy`: For video processing and editing
- `googletrans`: Google Translate API wrapper
- `requests`: For handling HTTP requests
- `time`: For handling time-related functions

You can install these libraries using the following command:
```bash
pip install torch diffusers moviepy googletrans requests
```


##Usage
Run the script and provide the desired input text in Arabic.
The script will translate the input text to English and generate a video sequence based on the translated text.
The generated video will be displayed using IPython display.
Feel free to modify the code and parameters according to your requirements.

##Notes
This code relies on a pre-trained model (damo-vilab/text-to-video-ms-1.7b) for video generation. Ensure that the model is available and compatible with the Diffusion Models framework.
The code uses the Google Translate API for translation. Make sure to provide valid API credentials or modify the translation mechanism accordingly.
The generated video frames are exported to a video file and displayed using the moviepy library. Adjust the width parameter of clip.ipython_display() for desired video display dimensions.


Make sure to replace the prompt variable with the desired text prompt for video generation.


