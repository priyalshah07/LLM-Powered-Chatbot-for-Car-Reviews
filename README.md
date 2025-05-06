# Car-ing is Sharing: A Prototype LLM-Powered Chatbot for Car Reviews
LLM-powered prototype for sentiment analysis, translation, QA, and summarization of car reviews — built for a fictional auto company to explore real-world NLP applications.

Welcome to my project built for the fictional company "Car-ing is Sharing" — a car rental and sales company looking to harness **LLMs** to improve customer interaction and insight extraction.

## Project Summary

This prototype demonstrates how Large Language Models (LLMs) can be leveraged for various tasks involving car customer reviews:

### Task Highlights:
1. **Sentiment Classification**
   - Model: `distilbert-base-uncased-finetuned-sst-2-english`
   - Outputs: Predicted sentiments
   - Evaluation: **Accuracy** and **F1 score**

2. **Translation for Spanish Market**
   - Model: `Helsinki-NLP/opus-mt-en-es`
   - Task: Translate the first review (2 sentences) to Spanish
   - Metric: **BLEU Score**

3. **Extractive Question Answering**
   - Model: `deepset/minilm-uncased-squad2`
   - Task: Answer the question “What did he like about the brand?” from review #2

4. **Summarization**
   - Model: `cnicu/t5-small-booksum`
   - Task: Generate a concise summary (~50 tokens) of the final review

## Tech Stack

- Python
- HuggingFace `transformers` & `evaluate`
- PyTorch
- BLEU, Accuracy, F1 metrics
