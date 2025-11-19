
# 📚 Semantic Book Recommender 

A Gradio-powered web app that recommends books using semantic search, emotion-based filtering, and category matching.
It uses sentence-transformer embeddings, a Chroma vector database, and emotion-annotated book metadata.


## Features

🔍 Semantic recommendations based on a natural-language description

📖 Filtered by category (e.g., Fiction, Nonfiction)

😊 Filtered by emotional tone (Happy, Sad, Suspenseful, etc.)

🧠 Uses HuggingFace sentence-transformers for embeddings

🗃️ Stores vectors using ChromaDB

🎨 Clean Gradio interface

🖼️ Shows book thumbnails and short captions


## Live Demo

👉 [Visit the live app on HuggingFace Spaces](https://huggingface.co/spaces/shoot4dastars/book-recommender)
## Run Locally

Clone the project

```bash
  git clone https://github.com/shoot4dastars/book-recommender
```

Go to the project directory

```bash
  cd book-recommender
```

Install dependencies

```bash
  pip Install -r requirements.txt
```

Run

```bash
  python app.py
```

It will start a local server such as:

```bash
  Running on http://127.0.0.1:7860
```


## Authors

- [Silon Pant](https://www.github.com/shoot4dastars)

