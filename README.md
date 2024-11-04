# Multi-Modal NLP Pipeline with Hugging Face

## Overview

This project implements a multi-modal natural language processing (NLP) pipeline utilizing pre-trained models from Hugging Face. The main objectives are to perform text classification, translation, and image captioning, while also enhancing the quality of existing datasets.

## Goals

- Leverage state-of-the-art pre-trained models for various NLP tasks.
- Create a robust pipeline for processing text and images.
- Improve and publish datasets on the Hugging Face Hub.

## Features

- **Emoji Classification:** Uses the `[cardiffnlp/twitter-roberta-base-emoji](https://huggingface.co/cardiffnlp/twitter-roberta-base-emoji)` model for predicting emojis based on text input.
- **Text Translation:** Implements the `[google/flan-t5-base](https://huggingface.co/google/flan-t5-base)` model for translating text between languages.
- **Image Captioning:** Generates intuitive captions for images using the [BLIP model](https://huggingface.co/docs/transformers/main/en/model_doc/blip), improving dataset descriptions.

## Datasets
This project utilizes the [mosunmola/fashion_image_caption-100](https://huggingface.co/datasets/mosunmola/fashion_image_caption-100) dataset for image captioning. Modifications include improved captions generated by the BLIP model, which have been published back to the Hugging Face Hub.

## Acknowledgements
Hugging Face for providing the models and datasets.
PyTorch for the underlying framework.
