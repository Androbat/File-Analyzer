# File-Analyzer

# 📄 Text File Analyzer

A memory-efficient CLI tool built in **Node.js** to analyze large text files. It processes input **line by line** using streams and reports word statistics like **frequencies**, **top-N words**, and more — all without loading the entire file into memory.

---

## 🚀 Features

- ✅ Efficient line-by-line file reading using streams
- 🔍 Counts word frequencies (case-insensitive)
- 📊 Displays the top-N most frequent words
- 🧠 Uses a map and priority queue for fast updates
- 🛠️ Easily extensible with filters, stopwords, CSV output, etc.

---

## 🧑‍💻 Technologies Used

- Node.js (`fs`, `readline`)
- TypeScript (optional but recommended)
- Regular Expressions for tokenization
- ES6 Map and custom MinHeap (Priority Queue)

---

## 📦 Installation

```bash
git clone https://github.com/yourusername/text-file-analyzer.git
cd text-file-analyzer
npm install
