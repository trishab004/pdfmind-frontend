# 🌟 PDFMind.AI - Frontend

📄✨ *Your AI-powered assistant to summarize and chat with PDFs — now in a beautiful, responsive, and theme-switchable interface!*

Welcome to the frontend repository of **PDFMind.AI** — a full-stack AI project built with love by [Trisha](https://github.com/TrishaB004). This is the user-facing part of the app where users upload PDFs, get AI-generated summaries, and ask questions directly to their documents. All in a sleek, mobile-friendly UI with dark/light mode toggle.

---

## 🖼️ Live Website

👉 [Visit PDFMind.AI](https://trishab004.github.io/pdfmind-frontend/) 
(Connects to a Render-hosted backend for summarization and Q&A)

---

## 🚀 Features

✅ Upload any PDF file  
✅ Get AI-generated summary instantly  
✅ Ask questions based on the uploaded PDF  
✅ Download the summary as `.txt`  
✅ Toggle between light and dark mode 🌞🌙  
✅ Fully responsive and mobile-friendly design  

---

## 🛠️ Built With

- **HTML5**
- **CSS3**
- **Vanilla JavaScript**
- **Google Fonts** (Outfit)
- **Hugging Face Transformers API** (via backend)
- **Render** (for backend deployment)

---

## 🧩 How It Works

1. User uploads a PDF using the upload button.
2. A `POST` request is sent to the `/summarize` route of the backend.
3. The backend extracts text using PyMuPDF and sends it to Hugging Face’s summarization model.
4. The summary is displayed beautifully in the frontend.
5. User can ask any question related to the PDF. The frontend sends a `POST` request to `/ask` with the question.
6. Backend processes it using Hugging Face’s QnA model and returns the answer.

---

