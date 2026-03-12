# 🔗 Markov Chain Session

A hands-on session exploring real-world applications of **Markov Chains** — covering **Autocomplete**, **PageRank**, and **Text Generation**.

---

## 📂 Project Structure

```
markov_chains_sesh/
├── markov_chain session_file.ipynb   ← Main notebook (Autocomplete + PageRank)
├── code.pdf                          ← Reference code document
├── data/
│   └── movie_script/
│       └── movie_lines.tsv           ← Dataset for Autocomplete
├── extra/
│   ├── sherlock_story_markov_chains.ipynb  ← Text Generation notebook
│   └── data/
│       └── sherlock/                 ← Sherlock Holmes story text files
└── README.md
```

### 🗂️ Main Folder — Autocomplete & PageRank

The main notebook (`markov_chain session_file.ipynb`) contains **two** implementations:

| # | Topic | What It Does |
|---|-------|-------------|
| 1 | **Autocomplete** (Primary) | Builds trigram, bigram, and unigram Markov chains from ~200K movie dialogues to predict the next word as you type. |
| 2 | **PageRank** (Secondary) | Demonstrates Google's PageRank algorithm using a simple 4-page link graph and iterative matrix computation. |

### 📁 Extra Folder — Text Generation

The extra notebook (`extra/sherlock_story_markov_chains.ipynb`) generates **Sherlock Holmes–style stories** using Markov Chains trained on the complete Sherlock Holmes text corpus.

---

## 🚀 Getting Started

Follow these **two steps** to run the notebooks:

### Step 1 — Open the Notebook in Google Colab

1. Download the `.ipynb` notebook file you want to run.
2. Go to [Google Colab](https://colab.research.google.com/).
3. Click **File → Upload notebook** and upload the downloaded `.ipynb` file.

### Step 2 — Download & Set Up the Dataset

For the **Autocomplete** notebook (`markov_chain session_file.ipynb`):

1. Download the dataset file: **`movie_lines.tsv`**
2. In your **Google Drive**, create a folder named exactly: **`autofill`**
3. Place the `movie_lines.tsv` file inside that folder.

> ⚠️ **Important:** The folder must be named **`autofill`** and the file must be named exactly **`movie_lines.tsv`** — the notebook reads from the path `/content/drive/MyDrive/autofill/movie_lines.tsv`.

For the **Text Generation** notebook (`extra/sherlock_story_markov_chains.ipynb`):

1. Upload the Sherlock Holmes `.txt` files (found in `extra/data/sherlock/`) to your Google Drive.
2. Place them in a folder named **`sherlock`** in your Drive root.

> The notebook reads from `/content/drive/MyDrive/sherlock/`.

---

## 🧠 Concepts Covered

- **Markov Chains** — Probabilistic model where the next state depends only on the current state.
- **N-grams** (Unigram, Bigram, Trigram) — Used to build transition probabilities for autocomplete.
- **PageRank Algorithm** — Ranks pages by simulating a random web surfer using a transition matrix and damping factor.
- **Text Generation** — Generates coherent text by sampling from learned Markov Chain transitions.

---

*Developed for the Markov Chain Learning Session.*
