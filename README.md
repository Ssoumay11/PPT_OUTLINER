# 🖼️ PPT Outliner – AI Powered PowerPoint Generator

An **AI-powered PowerPoint generator** that converts topics into structured slide decks.  
The system uses the **Google Gemini API** to generate outlines, fetches relevant images from the **Pexels API**, and auto-renders slides with **python-pptx** and **Pillow**.  

---

## ✨ Features
- 📝 **AI-Generated Outlines** – Converts topics into JSON-based slide structures (titles, content, slide types).  
- 🎨 **Automatic Slide Rendering** – Generates professional slide decks with consistent styling.  
- 🖼️ **Image Integration** – Fetches relevant images from **Pexels API** and embeds them into slides.  
- ⚡ **Automation** – Handles slide formatting and styling automatically.  
- 💻 **End-to-End Workflow** – From topic input → AI outline → final PowerPoint file.  

---

## 🛠️ Tech Stack
- **Python**
- **Google Gemini API** (AI-generated outlines)
- **Pexels API** (image integration)
- **python-pptx** (PowerPoint generation)
- **Pillow** (image processing)
- **Requests** (API calls)

---

## 🚀 Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/yourusername/ppt-outliner.git
cd ppt-outliner


Create a .env file with your API keys: or diect run into google colab

GEMINI_API_KEY=your_gemini_api_key
PEXELS_API_KEY=your_pexels_api_key

5. Run the script

python main.py

