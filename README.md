# 🧠 AI Autocorrect Tool

An AI-powered text correction application built using Python and Streamlit. This project performs:

- Spell correction
- Grammar correction
- Word suggestion generation
- Real-time text correction through a simple web interface

---

# 📌 Features

✅ Spell checking using custom word frequency dataset  
✅ Grammar correction using TextBlob  
✅ Word suggestion system  
✅ Interactive Streamlit web application  
✅ Easy-to-use interface  

---

# 🛠️ Technologies Used

- Python
- Streamlit
- TextBlob
- Collections Counter
- Regular Expressions (re)

---

# 📂 Project Structure

```bash
autocorrect-tool/
│
├── app.py                  # Streamlit frontend application
├── autocorrect.py          # Core autocorrect logic
├── data/
│   └── word.txt.txt        # Dataset containing valid words
└── README.md               # Project documentation
```

---

# ⚙️ Installation

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/autocorrect-tool.git
cd autocorrect-tool
```

## 2️⃣ Create Virtual Environment (Optional)

```bash
python -m venv venv
```

Activate virtual environment:

### Windows

```bash
venv\Scripts\activate
```

### Linux/Mac

```bash
source venv/bin/activate
```

---

# 📦 Install Required Libraries

```bash
pip install streamlit textblob
```

Download TextBlob corpora:

```bash
python -m textblob.download_corpora
```

---

# ▶️ Run the Application

```bash
streamlit run app.py
```

The application will open automatically in your browser.

---

# 🧪 How It Works

## Spell Correction

The application:

1. Loads a dataset of words
2. Calculates word probabilities
3. Generates possible word edits
4. Chooses the most probable correct word

## Grammar Correction

After spell correction, TextBlob improves sentence grammar and fluency.

---

# 📸 Application Workflow

1. Enter text in the input box
2. Click **Correct Text**
3. View:
   - Spell corrected text
   - Final AI corrected output
4. Use **Show Word Suggestions** for alternative word suggestions

---

# 📌 Example

### Input

```text
I havv a dreem
```

### Output

```text
I have a dream
```

---

# 🔧 Future Improvements

- Deep learning based NLP correction
- Multiple language support
- Voice input support
- Better contextual grammar checking
- Deployment on cloud platforms

---

# 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Push to your branch
5. Open a Pull Request

---

# 📜 License

This project is for educational and learning purposes.

---

# 👨‍💻 Author

Developed by Mohit Samal
