# 🧑‍💻 Prompt Engineering Practice Notebook

This Jupyter Notebook is designed to help you **practice and master Prompt Engineering** using OpenAI models, Hugging Face, and LangChain with ChromaDB.

---

## 📌 Features

1. **Basic Prompting**

   * Simple question answering
   * Role prompting (e.g., historian, tutor)

2. **Advanced Prompting**

   * Few-shot prompting
   * Chain-of-thought reasoning
   * JSON / structured outputs

3. **RAG (Retrieval-Augmented Generation)**

   * Uses **ChromaDB** as a local vector store
   * Stores documents (e.g., temples dataset)
   * Retrieves relevant context for better answers

4. **Parameter Playground**

   * Experiment with decoding parameters like:

     * `temperature` (creativity)
     * `top_p` (nucleus sampling)
     * `top_k` (token cutoff)
     * `max_tokens` (response length)
   * Compare outputs with different parameter settings

5. **Evaluation Section**

   * Try multiple variations of prompts
   * Observe how phrasing changes outputs

---

## 🚀 Setup

Install required libraries:

```bash
pip install openai langchain chromadb tiktoken transformers
```

---


```bash
# Windows
setx OPENAI_API_KEY "sk-xxxx"
# Linux/Mac
export OPENAI_API_KEY="sk-xxxx"
```

---

## 📖 How to Use

* Run each section in order inside Jupyter Notebook.
* Modify prompts and parameters to see different outputs.
* Test structured formats like **JSON** and **Markdown**.
* Use the **ChromaDB RAG section** to practice retrieval-based prompting.

---

## 🎯 Example Practice Ideas

* Rewrite the same question with different tones (formal, casual, poetic).
* Summarize long text into JSON bullet points.
* Use RAG to query your **own documents** (e.g., research papers, notes).
* Compare deterministic vs. creative generations by tweaking `temperature`.

---

## 📌 Next Steps

* Extend with more datasets in ChromaDB.
* Add evaluation metrics for outputs (BLEU, ROUGE).
* Deploy as a **Streamlit app** for interactive testing.

---

✨ With this notebook, you can **learn, experiment, and refine** your prompt engineering skills across multiple use cases.
