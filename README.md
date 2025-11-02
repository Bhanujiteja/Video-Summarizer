# 🎥 Video Summarizer AI Agent

An AI-powered **Multimodal Video Summarizer** built with **Streamlit**, **Phidata**, and **Gemini 2.0 Flash Exp** that analyzes uploaded videos and delivers actionable insights using both video understanding and supplementary web research via DuckDuckGo.

---

## 🚀 Key Features

✅ Upload & analyze videos (MP4 / MOV / AVI)
✅ Understands video scenes, actions & spoken content
✅ Uses **Gemini 2.0 Flash Exp** for multimodal reasoning
✅ Performs **web research** for additional context
✅ Provides detailed & user-friendly summarization
✅ Clean, responsive UI with Streamlit

---

## 🧠 Tech Stack

| Component       | Technology                       |
| --------------- | -------------------------------- |
| UI Framework    | Streamlit                        |
| AI Model        | Gemini 2.0 Flash Exp             |
| Agent Framework | Phidata                          |
| Web Search      | DuckDuckGo Tool                  |
| File Processing | Google Generative AI Upload APIs |
| Other           | Python, dotenv                   |

---

## 📌 Project Structure

```
📂 video_summarizer
├── app.py                # Main Streamlit app
├── requirements.txt      # Dependencies
├── README.md             # Documentation
```

---

## 🔧 Installation & Setup

### ✅ 1️⃣ Create & Activate Virtual Environment

(Example using Conda)

```sh
conda create -n video_summarizer python=3.10 -y
conda activate video_summarizer
```

### ✅ 2️⃣ Clone Repository

```sh
git clone https://github.com/<your-username>/Video-Summarizer-AI-Agent.git
cd Video-Summarizer-AI-Agent
```

### ✅ 3️⃣ Install Dependencies

```sh
pip install -r requirements.txt
```

### ✅ 4️⃣ Add API Key

Create a `.env` file in project root:

```
GOOGLE_API_KEY=YOUR_GEMINI_API_KEY
```

Get free API key → [https://aistudio.google.com/app/apikey](https://aistudio.google.com/app/apikey)

---

## ▶️ Run the App

```sh
streamlit run app.py
```

✅ The app will open in your browser at:

🔗 [http://localhost:8501](http://localhost:8501)

---

## 🧩 How It Works

```
Upload Video → Gemini Upload → Video Processing → AI Contextual Analysis →
          + Web Search → Combined Insights → Display Result
```

### 🧠 Agent Workflow:

1️⃣ Uploads & processes the video
2️⃣ Generates embeddings + temporal understanding
3️⃣ Combines user query with video context
4️⃣ DuckDuckGo fetches real-world data if necessary
5️⃣ Produces final summarized + contextual result

---

## ✅ Example Queries

> "Summarize the key highlights from this video."
> "What message is the speaker delivering?"
> "Is this video educational or promotional?"
> "What products or brands are shown in the video?"

---

## ⚠️ Notes

* Large videos may take longer due to processing
* Only supported formats: `.mp4`, `.mov`, `.avi`

---

## 🌱 Future Enhancements

✅ Downloadable summary report (PDF)
✅ Named entity extraction from video
✅ Scene timeline segmentation
✅ Multiple languages support

---

## 👨‍💻 Author

**Bhanuji Venkata Teja**
AI/ML Engineer | Conversational AI | Agentic Systems
📧 Email: *(your email here)*
🔗 LinkedIn: *(your link here)*

---

## ⭐ Show Support

If you like the project:

```
⭐ Star the repo
```

Thank you for exploring the **Video Summarizer AI Agent**! ✨
Excited to see what amazing insights you discover! 🎬🤖
