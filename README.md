
# 🤖 Cheeku – The Intelligent Word & Phrase Assistant

**Cheeku** is a smart chatbot built to help users understand language better. It can:
- 🔍 Provide **meanings** of English words  
- 🔄 Suggest **synonyms**  
- 🌐 Translate **phrases** into multiple languages

Built with 💡 simplicity and 💬 interactivity in mind, Cheeku is a perfect mini NLP project for learners and curious minds alike.

---

## 🚀 Features

- 📖 **Word Definitions** – Get accurate English meanings.
- 🧠 **Synonym Suggestions** – Find alternative words instantly.
- 🌍 **Translation Support** – Translate phrases using Google Translate API.
- ✅ **Interactive Command-line Interface** – Lightweight and fast.

---

## 🛠️ Tech Stack

- **Language**: Python 🐍
- **APIs**: Google Translate API, Dictionary API (e.g., Free Dictionary API)
- **Libraries**: `requests`, `json`, `googletrans` (or similar), `termcolor` for CLI aesthetics

---

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/cheeku-chatbot.git
   cd cheeku-chatbot


2. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

3. **(Optional)** Set up API keys if required (some dictionary APIs need it):

   * Create a `.env` file or export environment variables:

     ```bash
     export DICTIONARY_API_KEY=your_key_here
     ```

---

## ▶️ Usage

Run the chatbot using:

```bash
python cheeku.py
```

Then type:

* `meaning <word>` – to get definitions
* `synonym <word>` – to get synonyms
* `translate <phrase> to <language>` – to translate (e.g., `translate hello world to Hindi`)

Example:

```
> meaning ephemeral
"Ephemeral" means lasting for a very short time.

> synonym happy
Synonyms for happy: joyful, cheerful, delighted, content

> translate good morning to Spanish
Buenos días
```

---

## 📁 Project Structure

```
cheeku-chatbot/
├── cheeku.py
├── utils/
│   ├── dictionary.py
│   ├── translator.py
│   └── synonym.py
├── requirements.txt
└── README.md
```

---

## 🌍 Supported Languages

Cheeku can translate to and from a wide range of languages including:

* Hindi
* Spanish
* French
* German
* Japanese
* Tamil
* Bengali
* And many more...

---

## 📌 Future Enhancements

* [ ] Add voice input/output
* [ ] Add GUI (using Tkinter or Streamlit)
* [ ] Telegram bot integration
* [ ] Autocorrect & spelling suggestion

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repo
2. Create a new branch (`git checkout -b feature-name`)
3. Commit your changes
4. Push and open a Pull Request

---

## 📜 License

MIT License © Goutham Naroju
This project is open-source and free to use.

---

## 🙌 Acknowledgements

* [Google Translate API](https://cloud.google.com/translate/)
* [Free Dictionary API](https://dictionaryapi.dev/)
* [Python Requests Library](https://docs.python-requests.org/)

```


