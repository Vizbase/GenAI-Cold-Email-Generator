# 📧 GenAI-Cold-Email-Generator

Cold email generator for service companies using Groq, LangChain, and Streamlit. This tool automates the process of crafting personalized cold emails based on job postings. Users simply input the URL of a company's careers page, and the tool extracts job listings and generates tailored emails with relevant portfolio links. These links are matched using a vector database to align with specific job descriptions.

---

## ⚙️ Set-up

### Prerequisites

1. Obtain an API key from [Groq API Console](https://console.groq.com/keys).
2. Update the `.env` file located in the `app/` directory with the following:
   ```env
   GROQ_API_KEY=<your_api_key_here>
   ```

### Installation

1. Clone the repository and navigate to the project directory.
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Running the Application

Run the Streamlit app using the following command:

```bash
streamlit run app/main.py
```

---
- Attribution must be given in all copies or substantial portions of the software.

