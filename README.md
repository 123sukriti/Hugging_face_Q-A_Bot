# 📄 Document Q&A AI Assistant

An AI-powered assistant that answers user questions based on the content of uploaded PDF documents (e.g., the Indian Constitution). This project was developed in a Google Colab notebook using Hugging Face's FLAN-T5, Sentence-Transformers, FAISS, and pdfplumber.

## 🚀 Features

- Upload any PDF document.
- Extracts and chunks text using `pdfplumber`.
- Embeds chunks using `Sentence-Transformers`.
- Retrieves relevant chunks using `FAISS`.
- Generates context-aware answers using Hugging Face’s `FLAN-T5`.
- Fully executable on **Google Colab** with no local setup required.

## 🛠️ Technologies Used

- **Google Colab (Python)**
- **pdfplumber** – PDF text extraction
- **Sentence-Transformers** – semantic embeddings
- **FAISS** – similarity-based chunk retrieval
- **Hugging Face Transformers** – FLAN-T5 for question answering

## 🧠 How It Works

1. **PDF Upload** via Colab UI.
2. **Text Extraction** with `pdfplumber`.
3. **Chunking and Embedding** using `Sentence-Transformers`.
4. **Retrieval** of top relevant chunks with `FAISS`.
5. **Answer Generation** with Hugging Face’s `FLAN-T5` model.

## ▶️ Run on Google Colab

You can run the notebook directly here:  
📎 [Open in Google Colab](https://colab.research.google.com/drive/1aXEUq4FwQGe_va5ZPmErFO2HTpQr-q4l?usp=sharing)


## 📝 Example Use Case

- Upload: *Indian Constitution PDF*
- Ask: *“What is the importance of the Preamble?”*
- Answer: *“The Preamble outlines the guiding principles and core values of the Constitution...”*

## ✅ Future Improvements

- Add OCR for scanned PDFs  
- Integrate with Streamlit or Gradio for app deployment  
- Extend support to multilingual documents

## 🙋‍♀️ Author

**Sukriti Das**  
📫 [LinkedIn](https://www.linkedin.com/in/sukriti-das-39a097252) | 🌐 [Portfolio](https://celebrated-cupcake-aeed6c.netlify.app/) | 🧠 [GitHub](https://github.com/123sukriti)

## 📄 License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.
