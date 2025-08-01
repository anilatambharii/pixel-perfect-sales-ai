# Pixel-Perfect Sales Insights Engine

## Overview

This project demonstrates **OpenAI-powered prompt engineering** for rapid sales data summarization and transformation from raw Excel/CSV files into polished business insights—ideal for high-velocity tech/consulting environments.

- Ingests tabular Excel sales data
- Crafts dynamic prompts for GPT-3.5/4
- Produces client-ready summaries in <5 minutes
- Secure, modular, extensible for integration with APIs (e.g., Salesforce, AWS Lambda)
- Security-first: Input validation, safe API credentials

## Folder Structure

| Folder/File | Purpose                       |
|-------------|------------------------------|
| data/raw/   | Raw downloaded datasets      |
| src/        | Code modules & business logic|
| tests/      | Test scripts                 |
| main.py     | Command-line demo entrypoint |
| requirements.txt | Project dependencies     |


## Quickstart

1. Clone the repo and add your Kaggle sales dataset to `data/raw/`.
2. Set up `.env` with your `OPENAI_API_KEY`.
3. Install dependencies:  
   `pip install -r requirements.txt`
4. Run the CLI:  
   `python main.py`

See [src/] for full module docs.

