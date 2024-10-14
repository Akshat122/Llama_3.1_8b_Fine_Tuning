# Llama 3.1: Fine-Tuning for Hex Color Code Descriptions

This project demonstrates fine-tuning the **Llama 3.1** language model with **8 billion parameters** using techniques such as PEFT (Parameter-Efficient Fine-Tuning) and LoRA (Low-Rank Adaptation). The model has been trained to generate descriptions for hex color codes.

## Project Overview

- **Model**: Llama 3.1 (8B parameters)
- **Task**: Generating human-like descriptions for hex color codes
- **Dataset**: [Color Dataset on Hugging Face](https://huggingface.co/datasets/sreramr/colour)
- **Hardware**: Trained on a T4 GPU via Google Colab Notebook



## Run on Google Colab

You can run the project directly in your browser on Google Colab by clicking the link below:

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)]([https://colab.research.google.com/github/your-username/llama-3.1-hex-color-descriptions/blob/main/your_notebook.ipynb](https://colab.research.google.com/drive/1gVjj_qebnnZAJo1GQtlWzVkuyx_qVkYG?usp=sharing))

This will open the Jupyter Notebook in Google Colab, where you can fine-tune the model or run inference to generate color descriptions based on hex codes.


## Results

The model was fine-tuned for **60 steps** due to limited resources on Google Colab, using a **T4 GPU**. Despite the limited training time, the model demonstrated a promising ability to generate descriptive and creative outputs for various hex color codes. Further training could improve performance and generalization.

## Acknowledgments

- Special thanks to the [Color Dataset on Hugging Face](https://huggingface.co/datasets/sreramr/colour) for making the dataset available.
- Thanks to the Hugging Face team for the amazing Llama models.
- A big thank to **Unsloth**, the wonderful library that greatly facilitated the fine-tuning process.
