# 🎙️ AI Blog to Podcast Agent

Convert any blog article into a fully AI-generated podcast episode.

This project automatically extracts blog content from a given URL, transforms it into a conversational podcast-style script using a Large Language Model, and generates realistic audio using AI voice synthesis.

---

## 🚀 Overview

The AI Blog to Podcast Agent automates content repurposing by transforming written blog posts into engaging podcast episodes.

It performs:

- Blog content extraction  
- Script rewriting in podcast format  
- AI voice generation  
- Audio file output  

---

## 🧠 How It Works

1. A blog URL is provided as input.
2. The system extracts structured content using a web crawling API.
3. The content is rewritten into a conversational podcast script using an LLM.
4. The script is converted into natural-sounding speech.
5. The final podcast episode is saved as an MP3 file.

---

## 🛠 Tech Stack

- **Python**
- **OpenAI API** – Script generation
- **ElevenLabs API** – Text-to-speech synthesis
- **Firecrawl API** – Blog content extraction
- **python-dotenv** – Environment variable management

---

## 🔑 Environment Setup

Create a `.env` file in the root directory and add:

OPENAI_API_KEY=your_openai_key_here
ELEVENLABS_API_KEY=your_elevenlabs_key_here
FIRECRAWL_API_KEY=your_firecrawl_key_here


Ensure that API keys are kept secure and are not exposed in public repositories.

---

## ▶️ Running the Application


The application will:

- Accept a blog URL
- Generate a podcast-style script
- Convert it into audio
- Save the output locally

---

## 📂 Project Structure


---

## 💡 Use Cases

- Content repurposing for creators
- Automated podcast generation
- Educational audio content creation
- Marketing content transformation

---

## 📌 Future Improvements

- Multi-speaker podcast simulation
- Background music integration
- Web interface dashboard
- Batch processing support

---

## ⚠️ Disclaimer

This project requires valid API keys for external services. Usage may incur charges depending on provider pricing.
