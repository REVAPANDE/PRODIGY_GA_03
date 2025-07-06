# 🧠 Text Generation using Markov Chains

This repository contains my submission for **Task 3** of the **Prodigy Internship**, where I implemented a simple text generation algorithm using Markov Chains.

---

## 🚀 Task Overview

> Implement a simple text generation algorithm using Markov Chains. This involves creating a statistical model that predicts the probability of a character or word based on the previous one(s).

---

## 📂 Files in This Repo

| File | Description |
|------|-------------|
| `prodigy_ga_03.ipynb` | Colab notebook that builds the Markov model and generates text |
| `custom_data.txt` | Text corpus used for training (same as Task 1) |
| `README.md` | This file |

---

## 📈 Sample Output

![Screenshot 2025-07-06 155253](https://github.com/user-attachments/assets/cab3c534-0ba7-4ce4-aa07-2dfb3df39373)

---

## 🧠 How It Works

1. **Tokenization**: The input text is split into words.
2. **Model Building**: A Markov Chain is constructed using bigrams (n=2).
3. **Generation**: Starting from a random bigram, new words are predicted and appended until the desired length is reached.

---

## 🛠 Libraries Used

- `random`
- `collections.defaultdict`

---

## 🙋‍♀️ Author

**Reva Pande**  
B.Tech CSE (AI) @ IGDTUW  
[LinkedIn](https://linkedin.com/in/revapande) | [GitHub](https://github.com/revapande)

---

## ⭐️ If you found this helpful, consider starring the repo!
