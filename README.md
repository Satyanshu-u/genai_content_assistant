# 🧠 GenAI Content Assistant (CrewAI Edition)

An AI-powered content assistant built using [CrewAI](https://docs.crewai.com/), [LangChain](https://www.langchain.com/), and [OpenAI](https://platform.openai.com/), capable of generating:

- ✅ Blog posts  
- ✅ Emails  
- ✅ Summaries  
- ✅ Q&A answers  
- ✅ Creative writing

All through specialized expert agents.




## 🚀 Features

- 🧠 Powered by **CrewAI agents** for each content type  
- 🔐 Secure **OpenAI API key** entry using `getpass`  
- ✅ Built with **Gradio** for an easy-to-use UI  
- 📦 Safe for GitHub (no hardcoded secrets)  
- 🧰 Runs fully inside Google Colab  




## 📓 How to Run

1. **Open the Colab notebook**:  

2. **Set your OpenAI API key** securely when prompted.

3. **Choose a task type**, enter your input, and generate output instantly.




## 🛡️ OpenAI API Key Safety

To avoid exposing your API key:

- The notebook uses `getpass.getpass()` to securely input your key at runtime
- 🔐 **Your key is never saved or printed**
- ✅ Safe to upload the `.ipynb` file to public GitHub




## 🛠 Tech Stack

- [CrewAI](https://github.com/joaomdmoura/crewai)  
- [LangChain](https://www.langchain.com/)  
- [OpenAI API](https://platform.openai.com/)  
- [Gradio](https://www.gradio.app/)  
- Python (3.11+)
