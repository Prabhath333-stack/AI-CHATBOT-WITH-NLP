# AI-CHATBOT-WITH-NLP

"COMPANY NAME": CODETECH IT SOLUTIONS

"NMAE" : PRABHATH THUMMALA

"INTERN ID" : CT04DG393

"DOMAIN" : PYTHON

"DURATION" : 4 WEEKS

"MENTOR" : NEELA SANTHOSH

"DESCRIPTION":
This project is a modern, intelligent chatbot application built using Streamlit for the web interface and LangChain for natural language processing and conversation handling. It integrates the OpenAI API to power the large language model (LLM) backend, enabling the chatbot to understand and respond to complex queries in natural language.

The chatbot script starts by loading environment variables from a .env file using the python-dotenv library. This securely stores the OpenAI API key, avoiding hardcoding sensitive information in the code. It then initializes the ChatOpenAI class from LangChain with a configurable temperature setting, which controls the creativity of the responses.

To make the chatbot context-aware, a ConversationBufferMemory is used. This allows the chatbot to remember the conversation history within the session, making its responses more coherent and contextually appropriate.

The core logic is implemented using LangChain’s ConversationChain, which links the language model and the memory buffer together, enabling smooth interaction. When a user inputs a message through the Streamlit web interface, the chatbot processes the message using the conversation.predict() function and returns a generated response.

The frontend is built with Streamlit, which provides a responsive and easy-to-use web interface. The app maintains the conversation history using st.session_state, which stores each pair of user and bot messages in memory for the duration of the session. The messages are then rendered back to the user in a chat-like format.

Exception handling is implemented to catch any errors from the OpenAI API, such as rate limits or authentication failures. This ensures the app doesn’t crash unexpectedly and provides user-friendly error messages.

To run the chatbot, users install the required dependencies (streamlit, langchain, openai, python-dotenv), set their API key in a .env file, and start the app using streamlit run chatbot.py.

This chatbot can be extended with additional features like file upload (e.g., PDFs for Q&A), chat export, avatar integration, or deployment to a public web server. The modular design makes it a great base for educational, customer support, or interactive assistant projects.
![Image](https://github.com/user-attachments/assets/e7343105-dbf2-4f6c-89a0-71638cab8163)
