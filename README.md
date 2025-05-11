# 🌱 Plant Doctor AI

**Upload a photo + describe your plant problem → get a full personalized care plan!**

## Features
- 📸 Plant & Disease Detection from Image
- 🗣️ Input by Voice or Typing
- 📚 Searches plant care PDFs + web links using Chroma
- 🧠 Meta LLaMA 4 generates a full care guide
- 🎙️ Text + Voice output (Optional Visuals)

## How It Works
1. Upload image + describe the issue.
2. App identifies plant & possible disease.
3. Finds care advice from database.
4. Summarizes a custom care plan.
5. Outputs it via text, voice, and (optional) images.

## Installation
```bash
git clone https://github.com/yourname/plant-doctor-ai.git
cd plant-doctor-ai
pip install -r requirements.txt

## Technologies Used
- Streamlit
- OpenAI GPT-4o (for Care Plan Generation)
- Whisper (for Voice-to-Text)
- ChromaDB (for plant care guide retrieval)
- Unstructured (for loading PDFs and URLs)
