# ✉️ AI-Powered Cold Email Generator

An intelligent cold email generation tool designed for **service-based companies**.  
This application uses **Groq LLMs**, **LangChain**, and **Streamlit** to create highly personalized outreach emails by analyzing job listings directly from a company’s career page.

Users simply provide a careers page URL. The system:
- Extracts relevant job openings
- Understands role requirements using an LLM
- Matches them with suitable portfolio projects stored in a **vector database**
- Generates customized cold emails tailored to each role

---

## 💡 Real-World Use Case

Consider the following business scenario:

- A software services firm such as **Atliq** already has experienced engineers available.
- A business development executive from Atliq reaches out to Nike with a **targeted cold email**, offering a ready-to-deploy engineer whose skills closely match Nike’s requirements.

This tool automates that outreach process with **precision and personalization**.

---

## ⚙️ Getting Started

### 1. API Key Configuration
Generate a Groq API key from: `https://console.groq.com/keys`

Add your key:
```.env
GROQ_API_KEY=your_api_key_here
```

### 2. To get started, first install the dependencies using:
```
pip install -r requirements.txt
```
### 3. Run the atreamlit app -
```
streamlit run app/main.py
```
