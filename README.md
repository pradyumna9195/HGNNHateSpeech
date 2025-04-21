# HGNNHateSpeech

## Overview
This repository contains code and data for detecting hate speech in multimodal (image and text) content using Hypergraph Neural Networks (HGNN).

## Project Structure
- **Image/** - Contains image processing notebooks and data
  - `ImageHypergraph.ipynb` - Notebook for image hypergraph construction and analysis
  - `splits/` - Train/test/validation data splits
  - `img_txt/` - Image text data
  - `img_resized/` - Resized images for processing
  - `MMHS150K_GT.json` - Ground truth labels
  - `hatespeech_keywords.txt` - Keywords for hate speech detection

- **Text/** - Contains text processing notebooks and models
  - `text_embeddings.ipynb` - Notebook for generating text embeddings
  - `fasttext_model.model` - FastText embedding model
  - `word2vec_model.model` - Word2Vec embedding model
  - `textual_data_an1_cleaned_final.csv` - Cleaned textual data

## Description
This project uses hypergraph neural networks to detect hate speech in social media content that contains both images and text. The approach leverages the relationships between different modalities to improve detection accuracy.
