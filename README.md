# Pocket Text Lab – Python NLP in the Browser

Pocket Text Lab is a tiny browser-based NLP playground that runs **Python directly in the browser** using [PyScript](https://pyscript.net/). Paste any text (product copy, email drafts, short articles) and get instant insights:

- Word & sentence counts
- Estimated reading time
- Simple sentiment score (very lightweight lexicon-based)
- Top keywords (stopwords filtered out)

The entire app is a static page, making it a perfect fit for **GitHub Pages**.

---

## 🔧 Tech Stack

- **Python** (via PyScript / Pyodide)
- **HTML + Tailwind CSS** (CDN)
- No backend, no build pipeline required

---

## 🚀 Live Demo

Once deployed, add your GitHub Pages URL here, for example:

`https://dkranzmat.github.io/pocket-text-lab/`

---

## 🧠 Features

- **Paste & analyze** – Users can type or paste any text and run analysis with a single click.
- **Text statistics** – Word count, sentence count, unique word count, and rough reading-time estimate.
- **Sentiment hint** – Very small, hand-rolled positive/negative word lists to give a rough “leaning positive / neutral / negative” indicator.
- **Keyword chips** – Shows the most frequent non-stopword tokens as small keyword badges.
- **All local** – Analysis happens entirely in the browser; no data is sent to a server.

---

## 📂 Project Structure

```text
.
├─ index.html    # Single-page app: layout, Tailwind, PyScript logic
└─ README.md     # Project overview and usage
