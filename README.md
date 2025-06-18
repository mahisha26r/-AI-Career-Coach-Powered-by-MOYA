#  AI Career Coach – Powered by MOYA
# 🧠 AI Career Coach

AI Career Coach is a command-line assistant that helps users optimize resumes and prepare for interviews using powerful language models. Built with the [Moya](https://github.com/moyaproject/moya) multi-agent framework and OpenAI's GPT-4o, it offers contextual memory, resume scoring, and mock interview simulations.

---

## 🚀 Features

- 📄 **Resume Optimization**
  - ATS scoring out of 100
  - Keyword alignment and measurable impact suggestions
  - Professional resume feedback

- 🎤 **Mock Interview Trainer**
  - Behavioral, HR, and technical interviews
  - Real-time structured feedback
  - Practice questions with improvement tips

- 🧠 **Memory Tool**
  - Stores and retrieves past messages
  - Generates conversation summaries
  - Maintains continuity for better answers

- 📂 **Document Parsing**
  - Upload resumes and job descriptions in `.docx` or `.pdf`
  - Automatically extracts and uses file content

---

## 🏗️ Architecture

- **Agents**
  - `resume_agent`: Resume evaluation and scoring
  - `interview_trainer_agent`: Mock interviews with feedback
  - `classifier_agent`: Routes input to the right agent

- **MemoryTool**
  - `store_message`: Save user or assistant messages
  - `get_last_n_messages`: Fetch recent conversation
  - `get_thread_summary`: Get a text summary of conversation

- **Technologies**
  - Python 3.8+
  - OpenAI API (GPT-4o)
  - Moya Framework
  - PyPDF2 & python-docx

---

## 💻 Usage

1. **Set your OpenAI API key**
```bash
export OPENAI_API_KEY='your-api-key'
```

2. **Run the application**
```bash
python your_script_name.py
```

3. **Commands in the chat**
```bash
/resume path/to/your_resume.docx
/jd path/to/job_description.pdf
exit  # to quit
```

---

## 🛡️ Security

⚠️ The current script hardcodes the API key. You should load it from environment variables or use secure vaults for production.

---

## 📄 License

MIT License © 2025 AI Career Coach


