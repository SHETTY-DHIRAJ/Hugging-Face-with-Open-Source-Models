# Hugging-Face-with-Open-Source-Models

This project demonstrates the use of Hugging Face’s **transformers library** to perform various NLP, audio, image, and multimodal tasks. The models and weights are sourced from the Hugging Face Hub, enabling developers to innovate and create applications easily. Additionally, the project showcases how to deploy these functionalities as user-friendly AI applications using **Gradio** on Hugging Face Spaces.

## Project Overview

The availability of open-source models and pre-trained weights makes it possible to tackle a wide range of tasks with minimal effort. This project provides the building blocks needed to create pipelines for AI-enabled applications that are both powerful and easy to use.

### Key Tasks Covered

1. **Natural Language Processing (NLP)**:  
   - Turn a small language model into a chatbot capable of multi-turn conversations.
   - Translate between languages and summarize documents.
   - Measure similarity between two pieces of text for search and retrieval.

2. **Audio Tasks**:  
   - Convert audio to text using Automatic Speech Recognition (ASR).
   - Generate text-to-speech (TTS) outputs.
   - Perform zero-shot audio classification without fine-tuning.

3. **Image Tasks**:  
   - Identify objects or regions in an image using zero-shot segmentation.
   - Generate captions for images and perform image retrieval.
   - Implement visual question answering for image-based queries.

4. **Multimodal Tasks**:  
   - Combine object detection and TTS to generate audio narrations for images.

5. **Deployment**:  
   - Package applications into user-friendly Gradio apps.
   - Deploy on Hugging Face Spaces for easy cloud-based access.

---

## Project Structure

The project consists of 13 Jupyter notebooks, each dedicated to a specific task:

| Notebook File Name                        | Description                                              |
|-------------------------------------------|----------------------------------------------------------|
| `01_NLP.ipynb`                            | NLP tasks like chatbot creation.                        |
| `02_Translation_and_Summarization.ipynb`  | Language translation and document summarization.         |
| `03_Sentence_Embeddings.ipynb`            | Measure text similarity using embeddings.                |
| `04_Zero-Shot_Audio_Classification.ipynb` | Classify audio without fine-tuning a model.              |
| `05_Automatic_Speech_Recognition.ipynb`   | Convert audio to text with ASR.                         |
| `06_Text_to_Speech.ipynb`                 | Generate audio from text (TTS).                         |
| `07_Object_Detection.ipynb`               | Detect objects in images.                               |
| `08_Segmentation.ipynb`                   | Identify objects using zero-shot segmentation.          |
| `09_Image_Retrieval.ipynb`                | Perform image search and retrieval.                     |
| `10_Image_Captioning.ipynb`               | Generate captions for images.                           |
| `11_Visual_Q_and_A.ipynb`                 | Visual Question Answering (VQA).                        |
| `12_Zero_Shot_Image_Classification.ipynb` | Classify images using zero-shot classification.          |
| `13_Deployment.ipynb`                     | Package and deploy applications with Gradio.            |

---

## Prerequisites

- Python 3.8 or higher
- Jupyter Notebook for running code
- Key Libraries: Hugging Face Transformers, Gradio, matplotlib, pandas, numpy

## Acknowledgements

 - This project was inspired and developed based on the concepts learned in the [Open Source Models with Hugging Face](https://www.coursera.org/projects/open-source-models-with-hugging-face) on Coursera. Special thanks to the course creators for their comprehensive content and Hugging Face Hub for providing open access to high-quality models.
