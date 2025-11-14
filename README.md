# GPT-2 Text Generation

## Overview
This project uses a pre-trained GPT-2 language model to generate natural language text. The program loads a GPT-2 model from the Hugging Face Transformers library and generates text based on a given prompt.

## Features
- Uses pre-trained GPT-2 (Small, Medium, Large, or XL)
- Tokenizes and prepares input using the GPT-2 tokenizer
- Supports adjustable text length
- Generates human-like text based on prompt
- GPU supported (recommended for speed)

## Requirements
Install dependencies using:

pip install transformers torch sentencepiece

## How It Works
1. The GPT-2 tokenizer encodes the input prompt.
2. The pre-trained GPT-2 model generates output tokens.
3. The tokens are decoded into readable text.
4. The script prints the model-generated text.

## Example Code Structure
- Load tokenizer and model.
- Prepare input prompt.
- Generate output text.
- Decode and print the result.

## How to Run
Run the script:

python gpt2_text_generation.py

## Customization
You can modify:
- The prompt text
- Model size (gpt2, gpt2-medium, gpt2-large, gpt2-xl)
- max_length parameter for longer/shorter results
- temperature, top_k, top_p for creative variation

## Output
The program prints generated text based on the GPT-2 language model.
