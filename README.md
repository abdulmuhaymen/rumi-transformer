# 🕊️ Rumi LLM – A Transformer-Based Language Model for Poetic Generation

**Rumi LLM** is a custom Transformer-based language model trained exclusively on the poetic works of Jalāl ad-Dīn Muhammad Rūmī. This project is built entirely from scratch using PyTorch and features a fully handcrafted tokenizer and sequence modeling architecture. The goal is to explore how deep learning can emulate the mystic tone and rhythm of classical Persian poetry.

---

## 📌 Features

- **Custom Tokenizer**: Character-level tokenizer built specifically for Rumi’s text corpus.
- **Minimal Transformer Architecture**: Implements key components such as self-attention, positional encoding, and autoregressive generation.
- **From-Scratch Training Loop**: Includes batching, loss tracking, sampling, and evaluation.
- **Poetry Generation**: Capable of generating original verses in the style of Rumi after training.

---

## 📁 Project Structure

- `Rumi_LLM.ipynb` — Main notebook containing all code for tokenizer, model, training, and generation.
- `rumi_poetry11.txt` — Dataset file (uploaded manually).
- `README.md` — Project overview and documentation.

---

## 🧠 Model Description

This is a decoder-only Transformer language model with:
- Embedding layers for characters and positions
- A single self-attention block
- Feed-forward projection head
- Character-level softmax output layer

Despite being trained on a small poetic corpus, the model effectively learns structural and stylistic patterns.

---

## 🚀 Getting Started

1. Open the `Rumi_LLM.ipynb` notebook in Google Colab or Jupyter.
2. Upload the dataset file `rumi_poetry11.txt` when prompted.
3. Run all cells in order to preprocess data, train the model, and generate poetic text.

---

## 📈 Training Summary

- **Training loss**: ~1.6  
- **Validation loss**: ~2.1  
- These values indicate good learning given the limited and domain-specific data.

---

## 🔮 Output

After training, the model can generate new poetic text that mimics Rumi’s tone, meter, and rhythm. The generation is done character-by-character and produces stylistically coherent sequences.

---

## 📚 Future Enhancements

- Upgrade to **word-level tokenization** for improved semantics
- Implement **dropout**, **early stopping**, and **learning rate schedules**
- Experiment with deeper architectures and multi-head attention
- Integrate into a larger system such as a **RAG-based QA chatbot**

---

## 🤍 Acknowledgements

- Inspired by the poetry of **Rumi**
- Built using **PyTorch**
- Architecture influenced by foundational concepts in **Transformer** and **GPT-style** models

---

## 📜 License

This project is for academic and educational use. Please credit appropriately if reused or modified.

