# 📸 AI Visual Storyteller

A professional **Multimodal Generative AI** application that transforms visual sequences into structured narratives with synchronized audio. This project leverages the **Google Gemini 2.0 Flash-lite** model to bridge the gap between computer vision and creative writing.

---

## ✨ Key Features
* **Multimodal Processing:** Analyzes up to 10 images simultaneously to create a cohesive, chronological plot.
* **Dynamic Personas:** Generates stories with context-aware Indian character names and cultural nuances.
* **Genre-Driven Narratives:** Choose from 5 different styles (General, Moral, Mystery, Humorous, Adventure) with custom AI constraints.
* **Immersive Audio:** Integrated **Text-to-Speech (TTS)** using `gTTS` to provide instant audio playback of the generated story.
* **Real-time Performance:** Optimized with `gemini-2.0-flash-lite` for high-speed content generation.

---

## 🛠️ Tech Stack
* **Language:** Python 3.12+
* **AI Model:** [Google Gemini 2.0 Flash-lite](https://ai.google.dev/)
* **Web Framework:** [Streamlit](https://streamlit.io/)
* **Vision & Audio:** `Pillow` (Image Processing), `gTTS` (Speech Synthesis)
* **Environment Management:** `python-dotenv` for secure API handling.

---

## 🚀 Getting Started

### 1. Prerequisites
* Python 3.10 or higher.
* A [Google AI Studio API Key](https://aistudio.google.com/).

### 2. Installation
Clone the repository and install the dependencies:
```bash
git clone https://github.com/ArindamDeka09/GenAI_story_teller.git
cd GenAI_story_teller
pip install -r requirements.txt

---

## 💡 How It Works
1. **Frontend (app.py):** Built with Streamlit, it captures user images and genre preferences.
2. **AI Logic (story_generator.py):** The images are passed to the Gemini 2.0 Flash-lite model with a custom system prompt to ensure narrative consistency.
3. **Narration:** Once the text is generated, it's processed by Google Text-to-Speech (gTTS) to create a downloadable audio file.
