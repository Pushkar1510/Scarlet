# **S.C.A.R.L.E.T. - Smart Conversational AI Assistant**

S.C.A.R.L.E.T. (**Smart Conversational AI with Real-time Learning and Enhanced Technology**) is an advanced AI-powered assistant that integrates **natural language processing (NLP), real-time search, task automation, speech recognition, and text-to-speech capabilities** to provide an interactive user experience.

---
## 🚀 **Features**
- **Conversational AI** powered by **LLMs (Groq/OpenAI API)**
- **Real-time search & web scraping** for up-to-date information
- **Speech recognition & text-to-speech (TTS)**
- **Task automation** (open/close apps, play music, system control)
- **Secure API key management** using `.env`
- **GUI built with PyQt5** for easy interaction
- **Generates AI images** using Hugging Face API

---
## 🛠 **Tech Stack**
- **Python** (Core development)
- **PyQt5** (GUI)
- **Groq/OpenAI API** (NLP & AI chat capabilities)
- **SpeechRecognition** (Voice input)
- **edge_tts** (Text-to-speech conversion)
- **BeautifulSoup** (Web scraping for real-time search)
- **Hugging Face API** (Image generation)
- **AppOpener** (Automating app interactions)
- **Git & GitHub** (Version control)

---
## 📥 **Installation**
### **1️⃣ Clone the Repository**
```sh
 git clone https://github.com/Pushkar1510/Scarlet.git
 cd Scarlet
```

### **2️⃣ Create a Virtual Environment (Recommended)**
```sh
python3 -m venv .venv
source .venv/bin/activate  # For macOS/Linux
# OR
.venv\Scripts\activate    # For Windows
```

### **3️⃣ Install Required Dependencies**
```sh
pip install -r requirements.txt
```

---
## 🔑 **Setting Up API Keys (IMPORTANT)**
This project requires **API keys** to work correctly.

### **Create a `.env` File**
1. In the project root directory, create a **`.env`** file:
```sh
touch .env
```
2. Open `.env` and add the following (replace placeholders with your actual API keys):
```ini
HUGGING_FACE_API_KEY=your_huggingface_api_key
GROQ_API_KEY=your_groq_api_key
OPENAI_API_KEY=your_openai_api_key
SPEECH_RECOGNITION_KEY=your_speech_api_key
Username =your_name
Assistantname =assistant_name
InputLanguage = en
AssistantVoice = en-CA-LiamNeural
```
3. **DO NOT** share this file or push it to GitHub (it's already in `.gitignore`).

---
## 🚀 **Usage**
### **1️⃣ Run the Assistant**
```sh
python Main.py
```

### **2️⃣ Interact Using Voice or Text**
- You can **speak or type** queries.
- The assistant will **fetch real-time information, automate tasks, or generate responses**.

### **3️⃣ Example Commands**
| **Command** | **Response/Action** |
|------------|------------------|
| "Who is Albert Einstein?" | Fetches a detailed AI response |
| "What's the latest AI news?" | Scrapes and provides real-time news |
| "Open Chrome" | Opens Google Chrome |
| "Play music on YouTube" | Plays music via YouTube search |
| "Generate an image of a futuristic city" | Uses AI to generate an image |

---
## 🛠 **Customization**
- Modify **`.env`** to use your own API keys.
- Change **responses and behavior** in `Backend/Model.py`.
- Customize the **GUI** in `Frontend/GUI.py`.

---
## 📜 **License**
This project is **open-source** under the **MIT License**.

---
## 🤝 **Contributing**
1. Fork the repo
2. Create a new branch (`git checkout -b feature-branch`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to your branch (`git push origin feature-branch`)
5. Open a **Pull Request**

---
## 📬 **Contact & Support**
📧 Email: pushkargharat2001@gmail.com  
🔗 GitHub: [Pushkar1510](https://github.com/Pushkar1510)  


