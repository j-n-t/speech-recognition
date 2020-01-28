# Project: DNN Speech Recognizer

In this notebook, I've built a deep neural network that functions as part of an end-to-end automatic speech recognition (ASR) pipeline.

This process is divided in 3 steps:

* **STEP 1** is a pre-processing step that converts raw audio to one of two feature representations that are commonly used for ASR.
* **STEP 2** is an acoustic model which accepts audio features as input and returns a probability distribution over all potential transcriptions. After learning about the basic types of neural networks that are often used for acoustic modeling, I have conducted some investigations and designed my own acoustic model.
* **STEP 3** in the pipeline takes the output from the acoustic model and returns a predicted transcription.

Part of the code was made available as a template. My task was to add some new functionality to the sections identified with  **'IMPLEMENTATION'** in the header and to answer some questions regarding the implementation.

This project was developed in the context of **Udacity's Natural Language Processing nanodegree**.