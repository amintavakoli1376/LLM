# 🗨️ Dialogue Summarization with FLAN-T5

This project demonstrates how to use **Hugging Face Transformers** and the **Google FLAN-T5** model to automatically summarize dialogues from the [DialogSum dataset](https://huggingface.co/datasets/knkarthick/dialogsum).  
It takes long, multi-turn conversations and produces short, clear summaries similar to human-written ones.

---

## 📌 Features
- Load and explore the **DialogSum** dataset.
- Use the **FLAN-T5** pre-trained model for sequence-to-sequence summarization.
- Generate summaries from dialogues.
- Compare model-generated summaries to human-written ones.
- Experiment with **generation parameters** (`max_new_tokens`, `do_sample`, `temperature`) to optimize output quality.

---

## 📂 Dataset
- **Name:** [knkarthick/dialogsum](https://huggingface.co/datasets/knkarthick/dialogsum)
- Contains:
  - `dialogue` → multi-turn conversations.
  - `summary` → human-generated summaries.
