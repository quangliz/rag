### Overview
This repository contains implementations of RAG (Retrieval-Augmented Generation) techniques.
### API
I use the Google Gemini API in this repository because I can't afford the OpenAI API, but an OpenAI-compatible version will be included.
### Notes
- The hardware requirements are increasing as APIs from major companies have usage limits, so consider using local models on Colab.
- I don't want to quantize models (like Qwen1.5-1.8B) because they are small enough for text generation. Quantizing them would significantly reduce their performance.
### Usage
1. Clone this repository
```bash
git clone https://github.com/quangliz/rag.git
cd rag
```
2. Install requirements
```bash
pip install -r requirements.txt
```
3. Modify conf.env.example (then remove the ".example" suffix)