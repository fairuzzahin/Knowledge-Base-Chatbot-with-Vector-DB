# Knowledge Base Chatbot with Vector Database

A multilingual RAG-based Knowledge Base Chatbot that answers questions using content from a selected Bengali book available on Bengali Wikisource.

The system crawls the book and its chapter/subpage URLs, cleans and chunks the text, creates multilingual embeddings, stores them in a FAISS vector database, retrieves relevant content, and uses an LLM to generate answers with source citations.

---

# A. Book Information

## Book Title

**KapalKundala (কপালকুণ্ডলা)**

**Author:** Bankim Chandra Chattopadhyay  
**Edition:** 1870

## Bengali Wikisource

Official Bengali Wikisource book page:

https://bn.wikisource.org/wiki/কপালকুণ্ডলা_(বঙ্কিমচন্দ্র_চট্টোপাধ্যায়,_১৮৭০)

## Brief Description

*KapalKundala* is a Bengali novel written by Bankim Chandra Chattopadhyay and first published in 1870.

The novel is centered around Kapalkundala and Nabakumar and contains themes involving love, relationships, social customs, religion, and conflict. The book is an important work of Bengali literature.

This project converts the complete book content available through Bengali Wikisource into a searchable knowledge base. Users can ask questions in Bengali, and the chatbot retrieves relevant passages from the book before generating an answer.

The chatbot is designed to answer questions **only from the selected book**. If the requested information cannot be found in the book, the chatbot explicitly states that the information is not available in the selected book.

---

# B. Setup & Running Instructions

## Required Python Version

The project was developed and tested in:

**Python 3.13**

Google Colab can be used to run the complete project.

Python 3.10+ is recommended if running the project locally.

---

## 1. Clone the Repository

```bash
git clone https://github.com/fairuzzahin/Knowledge Base Chatbot with Vector Database.git
cd Knowledge Base Chatbot with Vector Database
