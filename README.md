# 🚀 AI Products – Streamlit Web App  

🔗 **Live Demo:** [divyansh.streamlit.app](https://divyansh.streamlit.app/)  

⚠️ **Important Notice:**  
When you visit the above link, **click "Yes, back this app up"** and wait for a few seconds while the app loads. This ensures the AI models and dependencies are initialized properly.  

---

## 📌 About This Project  
This **AI-powered Streamlit web app** provides three intelligent tools:  

1️⃣ **ATS (Application Tracking System)** – Analyzes resumes against job descriptions using AI.  
2️⃣ **YouTube Summarizer** – Generates detailed notes from YouTube video transcripts.  
3️⃣ **Invoice Extractor** – Extracts and interprets information from invoice images using AI.  

Built with **Google Gemini API, Streamlit, PyPDF2, YouTube Transcript API, and PIL**, this app simplifies resume screening, video summarization, and invoice data extraction.  

---

## 🛠️ Technologies Used  
- **Python** – Core programming language  
- **Streamlit** – Interactive UI framework  
- **Google Gemini API** – AI-powered text & image processing  
- **PyPDF2** – Extracts text from PDFs (used in ATS)  
- **YouTube Transcript API** – Fetches transcripts for summarization  
- **PIL (Pillow)** – Processes images for invoice extraction  

---

## 🚀 Features & Functionality  

### 1️⃣ AI ATS (Application Tracking System)  
📌 **What It Does:**  
- Reads your **resume PDF** and compares it with a **job description**  
- Provides a **match percentage** and **missing keywords**  
- Gives a **profile summary** with **improvement suggestions**  

📌 **How to Use:**  
1. **Enter a Job Description** in the text area.  
2. **Upload your Resume (PDF format).**  
3. Click **Submit** to analyze your resume.  

✅ **Powered by:** Google Gemini AI & PyPDF2  

---

### 2️⃣ YouTube Summarizer  
📌 **What It Does:**  
- Extracts **transcripts** from **YouTube videos**  
- Summarizes the content into **concise, structured notes**  

📌 **How to Use:**  
1. **Enter the YouTube video link.**  
2. Click **Get Detailed Notes** to extract & summarize the transcript.  

⚠️ **Note:** Some videos may not have transcripts available.  

✅ **Powered by:** YouTube Transcript API & Google Gemini AI  

---

### 3️⃣ Invoice Extractor  
📌 **What It Does:**  
- Reads **invoice images** (JPG, PNG, JPEG)  
- Extracts and analyzes invoice details  

📌 **How to Use:**  
1. **Upload an invoice image.**  
2. Enter a **question** about the invoice (e.g., "What is the total amount?").  
3. Click **Analyze Image** to get insights.  

✅ **Powered by:** PIL (Pillow) & Google Gemini AI  

---

## 🏁 Getting Started (For Developers)  

### 🔧 Prerequisites  
- Python **3.x** installed  
- API Key for **Google Gemini AI**  
- Dependencies from **requirements.txt**  

### 🔨 Installation & Setup  
```bash
# Clone the repository
git clone https://github.com/yourusername/ai-products-streamlit.git

# Navigate to the project folder
cd ai-products-streamlit

# Install dependencies
pip install -r requirements.txt

# Run the Streamlit app
streamlit run app.py
