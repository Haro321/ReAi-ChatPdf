# PDF Q&A System ( PATCHED YOU NEED TO CHANGE THE AI API )

## 📝 Overview

This project is a web-based application that allows users to upload a PDF document and ask questions about its content. The system extracts the text from the PDF, sends it along with the user's question to an AI model, and displays the generated answer. This provides a powerful way to quickly find and summarize information within PDF files without manual searching.

## ✨ Features

* **📄 PDF Upload & Processing**: Securely parses PDF files directly in the browser using `PDF.js`.
* **🤖 AI-Powered Q&A**: Integrates with the TypeGPT API to provide intelligent answers based on the document's content.
* **💅 Modern & Responsive UI**: A clean, intuitive, and mobile-friendly interface built with Tailwind CSS.
* **📋 Copy to Clipboard**: Easily copy the AI-generated answer with a single click.
* **🚀 Zero Backend**: The entire application runs on the client-side, making it easy to deploy on any static hosting platform.

## 🛠️ Technology Stack

* **Frontend**: HTML5, CSS3, JavaScript (ES6+)
* **Styling**: [Tailwind CSS](https://tailwindcss.com/)
* **PDF Parsing**: [PDF.js](https://mozilla.github.io/pdf.js/) by Mozilla
* **AI Model**: [TypeGPT API](https://chat.typegpt.net/) (Qwen/Qwen3-Next-80B-A3B-Instruct)

## 🚀 How to Use

1.  **Open the Application**: Launch the `index.html` file in a modern web browser.
2.  **Upload a PDF**: Click the "Upload your PDF" area and select a PDF file from your device.
3.  **Wait for Processing**: The application will extract the text from the document. A success message will appear when it's ready.
4.  **Ask a Question**: Type your question into the text area that appears.
5.  **Get an Answer**: Click the "Ask Model" button and wait for the AI to generate and display the response.

## ✅ To-Do & Future Improvements

Here is a list of potential features and enhancements to make the application even better:

* [ ] **Support More File Types**: Add support for `.docx`, `.txt`, and other common document formats.
* [ ] **Implement Streaming Responses**: Show the AI's answer as it's being generated (token by token) for a better user experience.
* [ ] **Add Conversation History**: Allow users to ask follow-up questions and see the history of their interaction with the document.
* [ ] **Better Error Handling**: Display more specific and user-friendly error messages for API failures or PDF parsing issues.
* [ ] **PDF Processing Progress Bar**: For larger files, show a visual indicator of the text extraction progress.
* [ ] **Advanced Chunking Strategy**: For very large documents (e.g., 100+ pages), implement a more intelligent chunking and vector-based retrieval strategy to send only the most relevant context to the model, saving on tokens and improving accuracy.
* [ ] **Highlight Sources**: Add functionality to highlight or reference the specific page or section of the PDF from which the answer was derived.

* [ ] **User Accounts**: Introduce a simple authentication system to allow users to save and view their document history.
