# Developer Sentiment Trends on Open-Source AI Models

A quantitative corpus study analyzing GitHub issue discourse across five major 
open-source AI/ML repositories to trace sentiment trends toward seven open-weight 
model families：Llama, Qwen, Gemma, DeepSeek, Phi, Kimi, and GLM， from 2023 to 2026.

## Data Collection
Issues were collected via the GitHub REST Search API from:
- pytorch/pytorch
- huggingface/transformers
- tensorflow/tensorflow
- ollama/ollama
- AUTOMATIC1111/stable-diffusion-webui

## Method
- Sentiment scoring via VADER
- Model-family tagging via keyword matching
- Aggregation by year and model family

## Files
- `Github_sentiment_datasets.ipynb` — data collection and tagging 

## Requirements
See `requirements.txt`
