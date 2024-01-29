# TOPSIS MODEL EVALUATION_102103471
## Text-Generation using pre-trained models
In the rapidly evolving field of natural language processing (NLP), text generation has emerged as a pivotal application with significant implications across various domains. With the advent of transformer-based models, such as GPT-3, BERT, and T5, the capabilities of automatic text generation have reached unprecedented levels of sophistication.This project aims to explore the capabilities of transformer models for text generation, leveraging the power of pre-trained language models to create coherent and contextually relevant text across a myriad of tasks. Transformers have revolutionized NLP by capturing long-range dependencies and contextual information, making them particularly well-suited for tasks like language modeling and text generation.

## Installattions
```bash
pip install transformers
pip install datasets
pip install rouge_score
```
## Work flow
## 1. Data Preparation
Ensure that your input data is well-prepared and suitable for text generation. This could include prompts, sentences, or any other format required by the chosen transformer models.

## 2. Model Selection
Choose multiple pre-trained transformer models from Hugging Face Transformers library. This could include models like GPT-3, BERT, T5, etc. Use these models to generate text based on your prepared data.

## 3. Text Generation
Implement the text generation process using the selected models. Here's an example using Hugging Face Transformers:

## 4. Evaluation Metrics Calculation
Compute evaluation metrics such as ROUGE scores and BLEU scores to assess the quality of the generated text. Use appropriate libraries or implement custom functions for these calculations.

## 5. Metrics Aggregation
Aggregate the calculated metrics for each model, creating a matrix where each row corresponds to a model and each column corresponds to a specific evaluation metric.

## 6. Normalization
Normalize the aggregated metrics using techniques like Min-Max scaling to ensure fair comparison, especially if the metrics have different scales.

## 7. TOPSIS Implementation
Implement the TOPSIS algorithm using the normalized metrics to determine the best model. Assign weights to each metric based on their importance, and calculate the TOPSIS score.

## 8. Visualizations
## 1. ![download (1)](https://github.com/Diehardgeek/TOPSISMODELEVALUATION_102103471/assets/127767001/939aa5f4-1ab0-4c96-bf60-6e8b40413230)
## 2. ![download](https://github.com/Diehardgeek/TOPSISMODELEVALUATION_102103471/assets/127767001/c225d0ad-342a-4b02-b796-71b510202eff)

# TOPSIS GRAPH
![The-working-flow-graph-of-EWM-and-TOPSIS](https://github.com/Diehardgeek/TOPSISMODELEVALUATION_102103471/assets/127767001/3c0dbe5c-e76d-4606-9252-ff396f7384c0)


