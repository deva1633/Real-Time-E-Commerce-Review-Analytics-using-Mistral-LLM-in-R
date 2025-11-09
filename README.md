# Real-Time-E-Commerce-Review-Analytics-using-Mistral-LLM-in-R
Real-time e-commerce review analytics using R and Mistral LLM via Ollama. This project cleans, processes, and analyzes customer reviews using AI-powered text modeling and visualization to extract insights, sentiments, and patterns from large-scale datasets. Real-time e-commerce review analytics using **R** and **Mistral LLM** via **Ollama**.  
This project cleans, processes, and analyzes customer reviews using AI-powered text modeling and visualization to extract **insights**, **sentiments**, and **patterns** from large-scale datasets.

---

## 🚀 Overview

The goal of this project is to build an **end-to-end text analytics pipeline** in R that leverages **Large Language Models (LLMs)** for understanding customer feedback in e-commerce.  
It integrates **data cleaning**, **language model inference (via Ollama + Mistral)**, and **visual analytics** using `ggplot2`.

---

## 📚 Key Features

- 🧹 **Automated Text Preprocessing** — Cleans and normalizes raw text using `textclean`.  
- 🤖 **LLM Integration via Ollama** — Connects to **Mistral LLM** through the `ellmer` package for AI-powered text generation.  
- 📊 **Sentiment & Insight Extraction** — Uses the model to summarize and classify customer sentiment.  
- 📈 **Visualizations with ggplot2** — Displays sentiment trends, word frequencies, and overall review distributions.  
- ⚡ **Scalable Pipeline** — Handles thousands of reviews efficiently with a progress-tracked loop.

---

## 🧠 Workflow

Raw Review Data (CSV)
->
Text Cleaning & Normalization
->
Mistral LLM via Ollama (Text Understanding / Sentiment)
->
Data Aggregation & Visualization
->
Insights Dashboard / Output CSV


---

## 🧾 Dataset

- **File Used:** `ecommerce_review.csv`  
- **Columns Expected:**
  - `text` → Review text  
  - *(Optional)* `rating`, `product`, or `date`  
- Ensure your dataset is saved in the project directory.




