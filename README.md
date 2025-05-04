# HelpMate AI Project

Simplifying insurance document queries with the power of Retrieval-Augmented Generation (RAG) and OpenAI's GPT models.

---

## ✨ Project Overview

HelpMate – RAG Insurance Assistant is a powerful solution designed to streamline the understanding and extraction of information from complex insurance documents. Traditional methods of navigating policy documents, claim procedures, and legal terminology can be time-consuming and frustrating. This tool leverages Retrieval-Augmented Generation (RAG) to blend state-of-the-art information retrieval with natural language generation, delivering precise and user-friendly answers to insurance-related queries.

Example Use Cases:

- “What does my health insurance policy cover?”
- “How do I initiate a vehicle insurance claim?”

---

## 🔍 Key Features

- 🌟 Accurate Information Retrieval: Quickly fetches relevant content from lengthy insurance documents using advanced embeddings.
- ⚡ Natural Language Responses: Offers concise and clear answers using modern NLP models.
- 🌐 Deployment Flexibility: Can be deployed locally or scaled for cloud-based enterprise environments.
- 🤖 AI-Driven Insights: Uses RAG pipelines to extract relevant answers directly from uploaded policy documents.
- ⚡ Fast and Efficient: Utilizes ChromaDB with caching to ensure high-speed retrieval.
- ✨ State-of-the-Art Generation: Supports OpenAI GPT-4, GPT-4o, Gemini API, or other top-tier LLMs for contextual response generation.
- 🖥️ User-Friendly Interface: Provides an intuitive and seamless experience for end users.

---

## 🛠️ Tech Stack

- **Language**: Python-In Jupyter Notebook
- **Frameworks/Libraries**: Transformers, ChromaDB, PDFplumber
- **APIs/Models**: OpenAI's GPT-4/ GPT-4o/ GPT-4o-mini
- **Tools used**: Jupyter Notebook

---

## 🚀 Getting Started

### Prerequisites

Ensure you have the following installed:

- Python 3.8+
- Docker (optional, for containerized deployment)

### Installation

1. Clone the repo:
   git clone https://github.com/RajaKalavala/HelpMateAI.git

2. Navigate to the project directory:
   cd helpmateAI.ipynb

3. Install the required dependencies:
   pip install -r requirements.txt

- Please note: OpenAI API keys are required for the project to function. You can obtain them from the OpenAI website and change the same in the code. We have updated the code and added more models to make it more dynamic in V2 of the project.

4. Run the main file from Jupyter environment:
   "helpmateAI.ipynb"

---

## 📖 Documentation

No documentation will be made available for this project since this project only uses technologies that already have their own documentation. Please refer to the following links for more information:

- [ChromaDB](https://docs.trychroma.com/)
- [PDFplumber](https://pypi.org/project/pdfplumber/0.1.2/)
- [Sentence Transformes](https://www.sbert.net/docs/)
- [OpenAI](https://platform.openai.com/docs/)

---

## 🛠️ Challenges/Issues Faced with fixes

- PDF Preprocessing: Tools like PDFMiner and PyPDF2 were tested but found insufficient. PDFplumber was chosen for its accuracy in text extraction.

- Table Extraction: Handling tabular data required a redesign of the data processing pipeline to work effectively with PDFplumber.

- Embedding Optimization: A caching mechanism was added to ChromaDB to prevent redundant re-embedding, enhancing system performance.

- Improved Relevance: A cross-encoder reranker was integrated to prioritize the most relevant document passages for higher-quality responses.

- Prompt Engineering: The system prompt was restructured to include few-shot examples and guiding instructions, significantly improving response accuracy.

---

## 🌟 Future Improvements

- [ ] Support for additional GPT models (e.g., Gemini, Claude AI, HuggingFace models)
- [ ] New feature additions for enhanced user experience
- [ ] Integration with other vector databases (e.g., Pinecone, Weaviate)

---

## 🛡️ License

Distributed under the MIT License.

---

## 💬 Contact

For any queries or feedback, feel free to reach out:

- **Email**: rajakalavala55@gmail.com
- **GitHub**: https://github.com/RajaKalavala
- **LinkedIn**: www.linkedin.com/in/rajakalavala

---
