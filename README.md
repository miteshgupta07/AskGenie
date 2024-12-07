# AskGenie: Conversational AI Chatbot with Persistent History 🤖

AskGenie is a powerful, multi-language conversational AI chatbot that delivers accurate, context-aware responses. Equipped with persistent chat history and customizable model settings, AskGenie is designed to provide a seamless, user-friendly experience for general knowledge queries and more.



## Features 🚀
- **Persistent Chat History**: Maintains the flow of conversation across queries.
- **Multi-Language Support**: Communicate in English, Spanish, French, German, or Hindi.
- **Customizable Models**: Choose from state-of-the-art models:
  - **LLaMA 3.1-8B**: Efficient for various language tasks.
  - **Gemma2 9B**: Offers nuanced and contextually rich responses.
  - **Mixtral**: Multi-modal capabilities for creative applications.
- **Adjustable Parameters**: Fine-tune temperature and max tokens to control output creativity and length.
- **Real-Time LangChain Tracing**: Enhanced debugging and performance optimization.



## Deployment 🌍
AskGenie can be deployed on **Streamlit** or **Hugging Face** for an intuitive and scalable user interface.



## Configuration 🛠️

### Model Selection
- **LLaMA 3.1-8B**: Optimal for general text generation tasks.
- **Gemma2 9B**: Ideal for nuanced, context-aware responses.
- **Mixtral**: Suitable for multi-modal (text and visual) tasks.

### Adjustable Parameters
- **Temperature**: Controls creativity in responses.
- **Max Tokens**: Limits the length of generated outputs.



## How It Works 📝 
1. User inputs are sent to the chosen model via LangChain.
2. Responses are generated based on the provided language and history context.
3. Persistent chat history ensures a continuous, natural conversation flow.



## Multi-Language Support 🌐
AskGenie supports five languages:
- **English**
- **Spanish**
- **French**
- **German**
- **Hindi**



## Usage Guide 📚
1. Clone the repository:
   ```bash
   git clone https://github.com/miteshgupta07/AskGenie.git
   cd AskGenie
2. Install Dependencies
   ```bash
   pip install -r requirements.txt
3. Set up API keys
 - Add your API keys  to repository secrets (for deployment) or .env (for local use).
4. Run the app locallly
   ```bash
   streamlit run app.py
   ```



## Security 🛡️ 
API keys are securely stored as **GitHub Repository Secrets** or in `.env` files for local development.



## Technologies Used 📊 
- **Streamlit**: For an interactive user interface.
- **LangChain**: To manage prompts and chat history.
- **ChatGroq**: High-performance conversational models.
- **Python**: Core programming language for logic and integration.



## Contributing 🤝 
Contributions are welcome! Please open an issue or submit a pull request for any improvements or feature suggestions.



## License 📜 
This project is licensed under the **MIT License**.



## Acknowledgments 🙏 
- **LangChain**: For robust history and prompt management.
- **Groq Models**: For providing state-of-the-art conversational AI capabilities.
- **Streamlit Community**: For helpful resources and support.
