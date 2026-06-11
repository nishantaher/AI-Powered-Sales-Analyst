# AI-Powered Superstore Sales Analyst

## Project Overview
An end-to-end AI-powered business analyst tool that enables
natural language querying over 10,000+ sales records using
a RAG (Retrieval Augmented Generation) pipeline.

## Tech Stack
- Python
- Pandas
- ChromaDB (Vector Database)
- Sentence-Transformers (Embeddings)
- Groq LLM (Free AI) — Get free key at console.groq.com
- Scikit-learn (ML Predictions)
- ipywidgets (Chat Interface)

## Features
- Natural language querying over sales data
- Semantic vector search using ChromaDB
- AI powered business insights using Groq LLM
- Sales data analysis using Pandas
- ML profit prediction using Scikit-learn

## How to Run
1. Install requirements:
   pip install -r requirements.txt
2. Get FREE Groq API key from console.groq.com
3. Add your key in Cell 5:
   os.environ["GROQ_API_KEY"] = "your-key-here"
4. Run all cells in order

## Output Screenshots

### Data Analysis Summary
![Analysis](screenshots/screenshot5.png)

### AI Question Answers
![Profitable Products](screenshots/screenshot1.png)
![Regional Sales](screenshots/screenshot2.png)
![Category Revenue](screenshots/screenshot3.png)
![Negative Profit](screenshots/screenshot4.png)

### ML Profit Prediction
![ML Prediction](screenshots/screenshot6.png)

## Sample Questions You Can Ask
- What are the most profitable products?
- Which city has the highest sales?
- What is the best performing category?
- Which region has lowest profit?

## ML Prediction
Predict profit based on:
- Sales amount
- Quantity
- Discount percentage

## Dataset
- Name: Superstore Sales Dataset
- Records: 9994
- Source: Kaggle
- Link: kaggle.com/datasets/vivek468/superstore-dataset-final

## Author
Built as part of Data Analysis + AI portfolio project.
