# 🎆 Comprehensive End-to-End QA GenAI Workflow 🎆

Welcome to our **End-to-End QA GenAI Workflow**, where **state-of-the-art technology** merges with an intuitive **user interface**! 🚀 This solution implements a **Retrieval-Augmented Generation (RAG)** technique, coupled with a **Streamlit-based interface** to manage PDF document uploads and queries. We incorporate the **Google Gemini API**—featuring the robust **Gemini Pro model**—to deliver high-quality **natural language comprehension** and **response generation**. Leveraging the **LlamaIndex** framework, we enable **efficient document indexing** and streamlined retrieval, ensuring timely and accurate responses to user queries. 🔍💬

With this setup, you can **upload**, **interact**, and **retrieve** insightful answers from your documents in a completely new way! 🎉

---

## ✨ Key Features ✨

- 🖥️ **Streamlit Interface** for smooth PDF uploads and user engagement.
- 🤖 **Google Gemini API** integration, utilizing the **Gemini Pro model** for top-tier language generation.
- 🗂️ **LlamaIndex** support for rapid and scalable content indexing and retrieval.
- 🛠️ **Modular Architecture** for straightforward maintenance and adaptability.
- 🚀 **High-Efficiency QA** processes that harness the power of your uploaded documents.

---

## 🏗️ System Architecture 🏗️

This solution follows a **modular** structure designed for scalability and maintainability. Its main building blocks include:

1. **Streamlit Frontend**: Provides a friendly interface for PDF uploads and queries.
2. **Document Processing**: Extracts text from uploaded PDFs for indexing.
3. **LlamaIndex Integration**: Indexes the extracted content to facilitate swift, accurate searches.
4. **Google Gemini API**: Leverages the **Gemini Pro model** to handle queries and generate human-like responses.
5. **Modular Code Design**: Keeps components separate, making it easier to update or extend.

---

## ⚙️ Setup Instructions ⚙️

Ready to get started with this cutting-edge GenAI solution? Follow these steps to set up your local environment:

### Prerequisites

- Python 3.10 or newer
- Valid **Google Gemini API** credentials
- **LlamaIndex** library installed

### Installation Steps

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/RohmaButt/RAG.git
   cd End-to-End-QA-GenAI-Project
   ```

2. Create and activate a Python virtual environment:

   ```bash
   python3.10 -m venv venv
   source venv/bin/activate   # On Windows, use `venv\Scripts\activate`
   ```

3. Install the required Python packages:

   ```bash
   pip install -r requirements.txt
   ```

4. Set up your **Google Gemini API** credentials. Follow [Google's official documentation](https://cloud.google.com/docs/authentication/getting-started) for setting up the API credentials.

5. Install **LlamaIndex**:

   ```bash
   pip install llama-index
   ```

---

## 🚀 **Running the Application** 🚀

Now that you're all set up, let’s get the app running:

1. Start the **Streamlit app**:

   ```bash
   streamlit run app.py
   ```

2. Open your browser and visit [http://localhost:8501](http://localhost:8501) to interact with the app. 🎉

3. **Upload a PDF file** and query it for intelligent responses generated using **Gemini Pro**!

---

## 🔄 **Workflow** 🔄

Here’s how the magic happens:

1. **Upload PDF**: The user uploads a PDF file through the **Streamlit UI**.
2. **Text Extraction**: The system extracts text content from the uploaded PDF.
3. **Document Indexing**: The text is indexed using **LlamaIndex** for **quick retrieval**.
4. **Query Generation**: The user submits a query, which is processed by the **Gemini Pro model**.
5. **Response Generation**: The system retrieves the relevant information and generates a **natural language response** using the **Gemini API**. 🎯

---

## 🔌 **API Integration** 🔌

This project utilizes the **Google Gemini API** (with the **Gemini Pro model**) for natural language generation. To interact with the API, you must set up your **Google Gemini API credentials** in the `config.py` file.

---

## ⭐ **Star the Project** ⭐

If you love this project, don’t forget to **star** it on GitHub! It helps us keep the project alive and motivates us to keep improving it. 🌟🚀

---
