# Prompt Strategy Benchmarking for Wellness Log Summarization

## Project Overview
This project explores different prompt strategies for summarizing semi-structured wellness logs using open-source LLMs.  
It demonstrates concise vs detailed summarization and evaluates readability using Flesch Reading Ease scores.

## Features
- Compare multiple prompt strategies (concise vs detailed)
- Use open-source LLMs from Hugging Face (`facebook/bart-large-cnn`)
- Evaluate generated summaries with readability metrics (`textstat`)
- Dummy wellness log dataset for demonstration

## Setup Instructions
1. Clone the repo:
```bash
git clone https://github.com/Kav-Gowda/prompt-bench-wellness-summarization.git 
```
2. Install dependencies:
```bash
pip install -r requirements.txt
```
3. Open Prompt_Benchmarking.ipynb in Google Colab or Jupyter Notebook and run cells.

## Usage
- Modify `wellness_logs` with your own data to test prompts.
- Add new prompt strategies and compare summaries.
- Evaluate output readability using `textstat`.

## Technologies
- Python
- Hugging Face Transformers
- Google Colab / Jupyter Notebook
- textstat
- pandas

