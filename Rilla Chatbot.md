Rilla Chatbot
Introduction
Welcome to the Rilla Chatbot, a friendly conversational agent designed to engage in text-based dialog with users. The bot uses GPT-3.5 and is built with Python, utilizing the LangChain framework for its memory capabilities.

Technologies Used
Python 3.x
LangChain
OpenAI GPT-3.5 Turbo
dotenv for environment variables
Setup
Clone this repository to your local machine.
Install the required packages listed in requirements.txt.
Copy code
pip install -r requirements.txt
Set up your OpenAI API key in a .env file:
makefile
Copy code
OPENAI_API_KEY=your-api-key-here
Running the Chatbot
Convert your Jupyter Notebook to a Python script, if you haven't done so already:
css
Copy code
jupyter nbconvert --to script YourNotebook.ipynb
Run the Python script from the terminal:
Copy code
python YourScript.py
You can interact with the chatbot by typing your queries and pressing enter. Type 'exit' to end the chat session.

Features
Memory Capabilities: Remembers previous conversations for a richer user experience.
Terminal Compatibility: Fully functional within a CLI environment.
License and Acknowledgements
This project is licensed under the MIT License. Special thanks to LangChain and OpenAI for their amazing frameworks and APIs.