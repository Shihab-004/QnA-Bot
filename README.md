# QnA-Bot
# ❓ Question Answering Bot

This project is a **Question Answering (QA)** system that takes a context (text/article)  
and answers a question based on that context using a pre-trained Hugging Face model.

## Features
- Takes any custom text as context.
- Answers user questions directly from the provided text.
- Uses Hugging Face `transformers` pipeline (DistilBERT).

## How to Run
1. Open the Google Colab notebook or clone this repo.
2. Install dependencies:
   ```bash
   pip install transformers
3. Run the notebook and enter:
   - **Context:** Your article or paragraph.
   - **Question:** A question related to the context.

## Example
**Context:** `RUET was established in 1964.`  
**Question:** `When was RUET established?`  
**Answer:** `1964`
