# LangChain and OpenAI GPT Integration with Memory Functionality

This project demonstrates the integration of LangChain with OpenAI's GPT model using a conversational memory that stores chat history in a file.

## Features

- **Conversation Memory**: Keeps track of conversation history and summarizes it.
- **File Storage**: Stores chat history in a JSON file.
- **Prompt Template**: Uses a template for human messages to interact with the model.
- **OpenAI Chat Model**: Utilizes the ChatOpenAI model from LangChain.

## Prerequisites

- Python 3.11
- OpenAI API
- Pipenv (for managing dependencies)
- `dotenv` package for loading environment variables

## Installation

1. **Clone the repository**:

   ```sh
   git clone git@github.com:catchnaren/tchat.git
   cd tchat
   ```

2. **Install dependencies**:

   ```sh
   pip install pipenv
   pipenv install
   ```

3. **Create a `.env` file**:
   ```sh
   touch .env
   ```
   Add your OpenAI API key to the `.env` file:
   ```env
   OPENAI_API_KEY=your_openai_api_key_here
   ```
4. **Activate the Virtual Environment**:
   ```sh
   pipenv shell
   ```

## Usage

Run the script:

```sh
python main.py
```
