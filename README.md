# LangChain: Chat with SQL Database

This project demonstrates how to use the LangChain library to create a conversational interface with an SQL database using Streamlit and Groq's Llama3 model. Users can connect either to a local SQLite3 database or a MySQL database and interact with it using natural language queries.

## Features
- Two database connection options: SQLite3 and MySQL.
- Integration with Groq LLM (Llama3-8b-8192 model).
- Natural language queries to interact with your SQL database.
- Conversation history is displayed using Streamlit's chat interface.
- Simple and easy-to-use interface via a sidebar for database connection setup.

## Usage
- Open the app in your browser(https://langchain-chat-with-sql-db-f6ae9wh3bfrnokrtbvyec4.streamlit.app/)
- Select the database connection option from the sidebar:
- Use SQLLite3 Database - Student.db: Automatically connects to the local student.db file.
- Connect to your SQL Database: Allows you to input MySQL credentials and connect to a remote database.
- Enter your Groq API key to enable the LLM functionalities.
- Type your query in the chat input to interact with the database using natural language.


## Configuration
- SQLite3: The student.db file should be placed in the same directory as app.py.
- MySQL: You will need to provide the MySQL credentials (host, user, password, database) via the Streamlit sidebar.

## Dependencies
- Python 3.7+
- Streamlit
- LangChain
- SQLAlchemy
- Groq API
