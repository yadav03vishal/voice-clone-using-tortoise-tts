# Voice Cloning using Tortoise TTS - GitHub Repository

## Overview

This GitHub repository showcases the work I have done in voice cloning using the powerful Tortoise TTS by Google Colab. The project aims to generate high-quality synthesized speech by leveraging the capabilities of Tortoise TTS, which is a state-of-the-art text-to-speech (TTS) model developed by Google.

## Introduction

Voice cloning has always been a fascinating field, and my project focuses on utilizing Tortoise TTS to clone voices from given audio samples. During the development process, I experimented with both local system implementation and Google Colab for the voice cloning task.

## Local System Implementation

In the initial stages of this project, I cloned the Tortoise TTS Git repository to my local system and conducted voice cloning experiments. However, I must mention that this approach turned out to be time-consuming and significantly slower than using Google Colab. For instance, the generation of a mere 10-second audio segment took approximately 5 to 6 hours on my local system, which was not feasible for practical use.

## Google Colab Implementation

Recognizing the limitations of the local system implementation, I decided to leverage the power of Google Colab for voice cloning with Tortoise TTS. This decision significantly improved the efficiency and reduced the processing time for generating voice samples. Google Colab's computing resources allowed me to execute the same voice cloning task, producing the desired output in a fraction of the time compared to my local system.

## Contents of the Repository

The repository primarily contains the following items:

1. **Voice Samples**: A collection of audio samples used as input for the voice cloning experiments. These samples were carefully selected to represent diverse voice characteristics.

2. **Output Samples**: A set of generated audio files that showcase the effectiveness of the voice cloning process using Tortoise TTS on Google Colab. These outputs highlight the successful replication of the given voice samples.

3. **Google Colab Notebook**: The Jupyter notebook used to perform the voice cloning task on Google Colab. This notebook includes the code, documentation, and explanations for the entire process.

## Running the Code in Google Colab

To experience the voice cloning process using Tortoise TTS in Google Colab, follow the step-by-step guide below:

1. Open the Google Colab notebook provided in the repository. You can do this by clicking on the provided link, which will redirect you to the Google Colab platform with the notebook loaded.

2. Click on the "Connect" button located in the upper right corner of the Google Colab interface. This will connect you to a virtual machine with the necessary resources for running the voice cloning experiments.

3. Execute the first cell by clicking on the "Play" button (triangle icon) or by using the keyboard shortcut Shift + Enter. This cell will install all the required packages and dependencies needed for the voice cloning process.

4. Proceed to the next cell, where you will find the code. In the second line of the code, insert the text that you want the cloned voice to speak. Modify this line accordingly to set the desired text for voice synthesis.

5. Additionally, in the fifth line of the code, you have the option to set the preset mode, which determines the quality of the cloned voice. Set it to "high quality for best voice" to achieve the highest possible voice quality.

6. After modifying the code as per your preferences, click on the "Run" button or use the keyboard shortcut Shift + Enter. Once you run this cell, you will be prompted to choose sample voice files to upload for cloning. Make sure the audio files are in .wav format.

7. Once the voice sample upload cell has completed processing, proceed to the last cell of the notebook. Click on the "Run" button to initiate the voice cloning process. This cell will take the input from the chosen voice sample and generate the cloned voice output.

Feel free to experiment with different text inputs, preset modes, and voice samples to explore the capabilities of Tortoise TTS for voice cloning.

## Acknowledgments

I would like to express my gratitude to the developers of Tortoise TTS for providing such a robust and powerful text-to-speech model. Additionally, I am thankful to the creators of Google Colab for offering a convenient platform to accelerate and enhance my voice cloning project.

---

Thank you for taking an interest in my voice cloning project using Tortoise TTS. If you have any feedback, questions, or suggestions, please feel free to open an issue or contact me.

Best regards,
VISHAL
