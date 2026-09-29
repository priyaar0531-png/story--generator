# AI Story Generator (GenAI, Python)

A Google Colab notebook that writes short stories with a generative language model (GPT-2 via Hugging Face Transformers).

## What it does
- Takes a genre, hero name, setting, and length
- Builds a story-opening prompt for the chosen genre
- Uses GPT-2 to continue the story, with adjustable temperature, top-k, and top-p sampling
- Cleans the output, prints it, and saves it as a `.txt` file

## Open in Colab
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR-USERNAME/story-generator-genai/blob/main/story_generator.ipynb)

(Replace `YOUR-USERNAME` with your GitHub username after uploading.)

## How to run
1. Open the notebook in Google Colab.
2. Choose **Runtime → Run all**.
3. Change the genre, hero, setting, and length in the settings cell, then run the generation cells again.

## Tech
Python, Hugging Face `transformers`, PyTorch, GPT-2.

## Limitations
GPT-2 is small, so stories may be repetitive or drift off topic. Larger or instruction-tuned models give better results.
