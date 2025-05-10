# 🧠 Research Assistant with LangChain

This is a research assistant application built using **LangChain** and **OpenAI's GPT-3.5** to help you generate research papers. The assistant answers queries related to research, utilizing multiple tools (like search and Wikipedia) to gather information and generate structured research responses.

## 🚀 Features

- Input a research query and receive a structured response.
- Utilizes external tools for searching and gathering information.
- Structured response with a summary, sources, and tools used.
- Powered by OpenAI's GPT-3.5 for generating responses.

## 🛠️ Technologies Used

- [LangChain](https://www.langchain.com/)
- [OpenAI API](https://platform.openai.com/)
- [pydantic](https://pydantic-docs.helpmanual.io/)
- [python-dotenv](https://pypi.org/project/python-dotenv/)

## 📦 Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/ai-resume-guide.git
   cd ai-resume-guide
   ```

2. **Create a virtual environment (optional but recommended):**

   ```
   python -m venv venv
   ```
   Activate the Virtual Environment:

   - Windows
   ```venv\Scripts\activate```
  
   - MacOS/Linux
   ```source venv/bin/activate```

3. **Install Dependencies**

   ```
   pip install -r requirements.txt
   ```
4. **Create a .env file in the root directory with your OpenAI API key:**
   ```
   OPENAI_API_KEY=your_openai_api_key_here
   
   ```

6. **Run the app:**
   ```
   python main.py
   ```

## 📸 Screenshot

Here is a screenshot of the research assistant running in the terminal:

![Research Assistant Screenshot](image/code.png)



## 🔐 Disclaimer
This tool uses the OpenAI API. Ensure your API key is kept secure and avoid uploading sensitive personal information.

## 📬 Contact
For feedback or inquiries, please reach out at harshkurware03@gmail.com.
