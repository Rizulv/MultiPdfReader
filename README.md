LangChainChatBot
Overview
LangChainChatBot is an interactive chatbot designed to query multiple PDFs and provide accurate responses based on their content. It leverages LangChain to connect with OpenAI, integrating chat memory for a seamless user experience. The project is deployed using Streamlit, offering a user-friendly interface.

Features
Multi-PDF Querying: Capable of querying over 10 PDFs simultaneously.
Chat Memory Integration: Remembers previous interactions for context-aware responses.
Accurate Document Responses: Provides precise answers based on PDF content.
Streamlit Deployment: User-friendly web interface for easy interaction.
Installation
Clone the repository

sh
Copy code
git clone https://github.com/yourusername/LangChainChatBot.git
cd LangChainChatBot
Install the required dependencies

sh
Copy code
pip install -r requirements.txt
Run the Streamlit app

sh
Copy code
streamlit run lm.py
Usage
Upload PDFs: Upload the PDFs you want the chatbot to query.
Interact with the Chatbot: Ask questions related to the content of the PDFs.
Review Responses: Get accurate and context-aware responses from the chatbot.
Project Structure
lm.py: Main script that runs the Streamlit app.
htmlTemplates.py: Contains HTML templates used in the Streamlit app.
.env: Environment variables for API keys and configuration (add this file with your keys).
Dependencies
Python: Version 3.7 or higher
LangChain: For connecting with OpenAI
OpenAI API: For NLP and chatbot functionality
Streamlit: For deploying the web interface
Other Libraries: Refer to requirements.txt
Contributing
Fork the repository
Create your feature branch (git checkout -b feature/AmazingFeature)
Commit your changes (git commit -m 'Add some AmazingFeature')
Push to the branch (git push origin feature/AmazingFeature)
Open a Pull Request
License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgements
OpenAI: For the powerful NLP models.
LangChain: For the seamless integration with OpenAI.
Streamlit: For the easy-to-use deployment interface.
