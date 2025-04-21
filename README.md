
# 🦜 LangChain URL/YouTube Summarizer

This is a simple and powerful **Streamlit web app** that summarizes the content of a **YouTube video** or a **web article** using **LangChain**, **Groq's LLMs**, and `YoutubeLoader` / `WebBaseLoader`.

### 🔗 Live Use Case:
Paste a **YouTube video URL** or any **web URL**, and get a **clean summary** of the content in under **300 words** — powered by the **LLaMA-3 model via Groq API**.

---

## ✅ Features

- 🧠 Uses **Groq’s LLaMA-3 model** for summarization
- 🔗 Summarizes both **YouTube videos** and **web pages**
- 🧱 Based on **LangChain summarization chains**
- 🌐 Clean UI with **Streamlit**
- 🛡 URL validation using `validators`

---

## 🛠 How It Works

1. You enter your **Groq API key** in the sidebar.
2. Enter a **YouTube URL** or **web article URL**.
3. The app:
   - Loads video/article content using `YoutubeLoader` or `WebBaseLoader`
   - Sends the content to LLaMA-3 via LangChain's summarization chain
   - Returns a clean summary in ~300 words

---

## 🚀 Getting Started (Setup Instructions)

Follow these steps to run the app locally:

### 1. Clone the Repo

```bash
git clone https://github.com/yasirwali1052/Url-YT-Summarize.git
cd Url-YT-Summarize
```

### 2. Create a Virtual Environment (Optional but Recommended)

```bash
python -m venv venv
venv\Scripts\activate   # Windows
```

### 3. Install Required Packages

```bash
pip install -r requirements.txt
```

### 4. Run the App

```bash
streamlit run app.py
```

---

## 🔐 Get Your Groq API Key

1. Go to: [https://console.groq.com/keys](https://console.groq.com/keys)
2. Sign up or log in
3. Generate your API key
4. Copy and paste it into the **sidebar input** of the app

---

## 🧪 How to Use

1. Run the app: `streamlit run app.py`
2. In the sidebar:
   - Paste your **Groq API Key**
3. In the main area:
   - Paste a **YouTube** or **Web URL**
   - Click **"Summarize the Content from YT or Website"**
4. ✅ Get a clear and concise summary of the content

---

## 📦 Requirements

Here’s the content of `requirements.txt`:

```
streamlit==1.18.1
langchain==0.0.148
langchain_groq==0.1.4
validators==0.20.0
```

> Note: Make sure you have Python 3.8 or later installed.

---

## 📁 Folder Structure

```
Url-YT-Summarize/
│
├── app.py                # Main Streamlit app
├── .env                  # For storing your Groq API key (optional)
├── requirements.txt      # All required dependencies
└── README.md             # You’re reading this!
```

---


## 🙌 Author

Built with ❤️ by [yasirwali1052](https://github.com/yasirwali1052)



