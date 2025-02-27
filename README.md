# **🔍 AI Web Search Assistant** 🤖  
A **Streamlit-powered AI web search tool** that leverages **GPT-4o** and **DuckDuckGo** to fetch real-time search results and generate responses.  

---

## **📌 Overview**
This **AI-powered web search assistant** allows users to enter a query and get **real-time web search results** using **DuckDuckGo**, enhanced by **GPT-4o's** reasoning capabilities.  

💡 **Key Features**:  
✔️ **Web Search via DuckDuckGo** 🦆  
✔️ **GPT-4o Integration for Smarter Responses** 🤖  
✔️ **User-Friendly Interface with Streamlit** 🎨  
✔️ **Secure API Key Input** 🔑  
✔️ **Supports Conversational AI & Information Retrieval** 📚  

---

## **📂 Folder Structure**
```
📦 ai-assistant-web-searching
│── 📜 .gitignore          # Ignore unnecessary files
│── 📜 README.md           # Project documentation (this file)
│── 📜 requirements.txt    # Dependencies
│── 📂 .streamlit          # Streamlit configuration
│── 📂 .devcontainer       # VS Code development container settings
│── 📜 streamlit_app.py    # Main Streamlit app
│── 📜 ai_websearch.py     # Backend logic for AI-powered search
```

---

## **🚀 Getting Started**
### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/Anou26/ai-assistant-web-searching.git
cd ai-assistant-web-searching
```

### **2️⃣ Set Up a Virtual Environment**
```bash
python -m venv ai-search-env
source ai-search-env/bin/activate  # macOS/Linux
ai-search-env\Scripts\activate     # Windows
```

### **3️⃣ Install Dependencies**
```bash
pip install -r requirements.txt
```

### **4️⃣ Run the Streamlit App**
```bash
streamlit run streamlit_app.py
```

---

## **🛠️ Features**
- 🔍 **Searches the web** in real-time using **DuckDuckGo API**.  
- 🤖 **Uses GPT-4o** to summarize and analyze search results.  
- 📜 **Simple UI** with **Streamlit** for easy access.  
- 🔑 **Secure API Key Input** (User provides their own OpenAI API Key).  
- 🚀 **Fast & Lightweight** for quick, reliable responses.  

---

## **📜 How It Works**
1. **User Inputs Query**: Enter a search query in the text box.  
2. **DuckDuckGo Fetches Results**: Retrieves **real-time search data**.  
3. **GPT-4o Processes Data**: Enhances and **summarizes search results**.  
4. **Results Displayed**: The **best response** is shown in the Streamlit app.  

---

## **⚙️ Dependencies**
The project requires the following Python libraries:  
```txt
streamlit==1.29.0
pandas>=1.3.0
scikit-learn
altair>=4.0
phi
```
Install all dependencies using:
```bash
pip install -r requirements.txt
```

---

## **📌 Future Improvements**
🚀 **Support More Search Engines** (Google, Bing, etc.)  
🚀 **Enhanced Answer Summarization** using LLMs  
🚀 **Conversational AI Mode** for interactive responses  
🚀 **Deploy as a Web App** (Heroku/Vercel)  
