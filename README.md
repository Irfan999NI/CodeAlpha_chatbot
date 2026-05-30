# CodeAlpha_chatbot
# Pasha Poultries NLP Chatbot 🐔

An interactive, client-side FAQ chatbot built for wholesale poultry suppliers. This project demonstrates core Natural Language Processing (NLP) concepts entirely within the browser using JavaScript. 

## 🚀 Features
* **No Backend Required:** Runs entirely in the browser using Vanilla JavaScript.
* **Bag of Words (BoW) Model:** Converts sentences into mathematical vectors based on a dynamic vocabulary.
* **Cosine Similarity Algorithm:** Compares user input vectors against predefined FAQ vectors to find the most mathematically similar question.
* **Text Preprocessing:** Implements custom tokenization, lowercasing, punctuation stripping, and stop-word removal.
* **Modern UI/UX:** Built with Tailwind CSS, featuring smooth chat bubbles and simulated typing indicators.

## 🛠️ Technologies Used
* HTML5 / Vanilla JavaScript (ES6 Classes)
* Tailwind CSS (via CDN)
* Math & NLP (Custom Cosine Similarity & Vectorization implementation)

## 💡 How it Works
1. The `NLPEngine` class is initialized with a dataset of FAQs.
2. The engine builds a unique vocabulary list from all questions.
3. When a user asks a question, the text is cleaned (stopwords removed) and converted into an array of tokens.
4. The tokens are mapped into a Vector.
5. The vector is compared against all FAQ vectors using Cosine Similarity. The answer associated with the highest score is returned to the user.
