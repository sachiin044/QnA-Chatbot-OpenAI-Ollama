# QnA Chatbot With OpenAI & Ollama 🚀  

An advanced Q&A chatbot built using **OpenAI's GPT models** and **Ollama's open-source models**, integrated into a user-friendly **Streamlit web app**. This project enables users to interact with AI using both cloud-based (OpenAI) and local (Ollama) models.  

## ✨ Features  
- 🔥 **Dual AI Model Support:** OpenAI's GPT (`gpt-4o`, `gpt-4-turbo`, `gpt-4`) and **Ollama’s open-source LLMs**.  
- 🌐 **Web-based Interface:** Built with **Streamlit** for real-time interaction.  
- 🎯 **Customizable AI Settings:** Adjust **temperature, max tokens**, and switch between OpenAI & Ollama models.  
- 🛠 **Flexible API Integration:** Users can input their own **OpenAI API key**.  
- ⚡ **Local AI Processing:** Run open-source models with **Ollama**, reducing cloud dependencies.  

## 🛠 Installation  

1. **Clone the repository:**
   
   ```sh
   git clone https://github.com/your-github-username/QnA-Chatbot-OpenAI-Ollama.git
   cd QnA-Chatbot-OpenAI-Ollama
   
2. **Create a virtual environment and activate it:**
   
   ```sh
   python -m venv venv  
   source venv/bin/activate  # On Windows, use venv\Scripts\activate
   
3. **Install dependencies:**

   ```sh

    pip install -r requirements.txt
     
4. **Set up OpenAI API Key (Optional, for OpenAI models only):**
   Create a .env file and add:

   ```sh
   echo "OPENAI_API_KEY=your-api-key-here" > .env

5. **Run the chatbot app:**

   ```sh
   streamlit run app.py

## **📂 Project Structure**
📁 QnA-Chatbot-OpenAI-Ollama
│── app.py                # Main chatbot application /n <br>
│── requirements.txt       # Dependencies /n <br>
│── .env                   # API key configuration (not included in repo)
│── README.md              # Documentation
│── image.png              # Screenshot of chatbot UI


    

