
# PocketSmart 🧠✨

PocketSmart is a **Flask-based Generative AI application** that integrates with the **Groq API** to deliver smart, AI-powered responses through a simple web interface.  
It’s designed as a lightweight, modular project for experimenting with **prompt engineering, generative AI workflows, and ethical AI practices**.



## 🚀 Features
- Flask web application (`app.py`)
- Generative AI integration via Groq API
- Secure environment variable handling (`.env`)
- Template rendering with Jinja2 (`templates/`)
- Static assets for styling (`static/`)
- Dependency management with `requirements.txt`



## 📂 Project Structure
```
PocketSmart/
│
├── app.py              # Main Flask application
├── requirements.txt    # Python dependencies
├── .env                # Environment variables (ignored in Git)
├── .gitignore          # Git ignore rules
├── static/             # CSS, JS, images
└── templates/          # HTML templates
```

---

## ⚙️ Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Seema8904/pocketsmart.git
   cd pocketsmart
   ```

2. **Create a virtual environment**
   ```bash
   python -m venv .venv
   .venv\Scripts\activate   # On Windows
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Set up environment variables**
   - Create a `.env` file in the project root:
     ```
     GROQ_API_KEY=your_new_api_key_here
     ```


## ▶️ Usage
Run the Flask app:
```bash
python app.py
```
Then open your browser at:
```
http://127.0.0.1:5000/
```





