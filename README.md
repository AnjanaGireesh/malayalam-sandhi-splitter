# 🌺 Malayalam Sandhi Splitter

A hybrid Sandhi splitter for Malayalam that uses a **Transformer model** with **rule-based fallback logic** to split compound words into their root components.

---

## 📘 Project Overview

This notebook demonstrates the process of:
- Preprocessing a dataset of Malayalam compound words and their splits
- Training a Transformer-based sequence-to-sequence model using TensorFlow
- Handling difficult or unseen words with handcrafted **rule-based Sandhi splitting logic**
- Providing word-by-word predictions with grammatical prioritization (nouns → verbs)

---

## 🔧 Features

- ✅ Transformer model for accurate sequence prediction  
- 🧠 Rule-based backup for rare/unseen Sandhi cases  
- 📊 Evaluation metrics like accuracy and loss  
- 📜 Display of original and split words side by side  
- 🧪 Designed for both single-word and passage-level input  

---

## 📂 Dataset Format

Each line in the dataset contains:
input_word split1 split2

Example:
സർവ്വവിജ്ഞാനകോശം സർവ്വ വിജ്ഞാനകോശം
