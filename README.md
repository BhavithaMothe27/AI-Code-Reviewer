💻 AI Code Reviewer

An AI-powered Code Review application that uses Google Gemini to analyze source code, identify bugs, suggest improvements, detect security issues, review coding style, and generate improved code. The application also supports code conversion between programming languages through an interactive Gradio interface.

---

🚀 Features

- 💻 AI-powered code review
- 🐞 Detect coding errors and bugs
- ⚡ Performance optimization suggestions
- 🎨 Code style recommendations
- 🔒 Security issue detection
- 🔄 Code conversion between programming languages
- ⭐ Code quality rating out of 10
- 🌐 Interactive Gradio web interface

---

🛠️ Technologies Used

- Python
- Google Gemini API
- Google Generative AI SDK
- Gradio

---

📂 Project Structure

```
AI-Code-Reviewer/
│
├── app.py
├── AI_Code_Reviewer.ipynb
├── requirements.txt
├── README.md
└── .gitignore
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/BhavithaMothe27/AI-Code-Reviewer.git

cd AI-Code-Reviewer
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

▶️ Run the Application

```bash
python app.py
```

---

Configure Gemini API

Replace:

```python
genai.configure(api_key="YOUR_GEMINI_API_KEY")
```

with your own Gemini API key.

---
Workflow

1. Paste your source code.
2. Select the input programming language.
3. Select the output programming language.
4. Click **Submit**.
5. Gemini analyzes the code and provides:
   - Summary
   - Bug Detection
   - Performance Improvements
   - Code Style Suggestions
   - Security Analysis
   - Improved Code
   - Code Rating

---
📸 Example

Input Language
Python

Output Language
Java

Output

- Code Summary
- Bugs Found
- Performance Improvements
- Security Issues
- Improved Java Code
- Rating: 9/10

---

📦 Requirements

- Python 3.9+
- Google Gemini API Key
- Internet Connection

---

Future Enhancements

- Support for more programming languages
- Syntax highlighting
- File upload support
- Download reviewed code
- GitHub repository integration
- Code complexity analysis

---

Author

Bhavitha Mothe

---

📄 License

This project is developed for educational and learning purposes.
