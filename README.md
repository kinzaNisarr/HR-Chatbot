# AI Chatbot

Welcome to the HR Chatbot repository! This project is designed to streamline HR inquiries for employees by leveraging the power of OpenAI's API and Streamlit for a user-friendly web application.

## Overview

The FutureTech Solutions HR Chatbot is an AI-powered assistant designed to help employees with their HR-related inquiries. It provides comprehensive information on company policies, employee benefits, leave requests, and payroll information.

## Features

- **Personalized Assistance**: The chatbot greets employees by their name and ID.
- **HR Inquiries**: Handles questions related to company policies, employee benefits, leave requests, and payroll.
- **User-Friendly Interface**: Built with Streamlit for an intuitive and easy-to-use web application.
- **Secure**: Uses environment variables to securely manage API keys.

## Setup

### Prerequisites

- Python 3.6 or higher
- An OpenAI API key
- An OpenAI Assistant
- Streamlit

### Installation

1. **Clone the repository**
    ```bash
    git clone https://github.com/rajikudusadewale/hr-chatbot.git
    cd HR-chatbot
    ```

2. **Create a virtual environment**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install dependencies**
    ```bash
    pip install -r requirements
    ```

4. **Set up environment variables**
    - Create a `.env` file in the root directory of the project.
    - Add your OpenAI API key to the `.env` file:
        ```
        OPENAI_API_KEY=your_openai_api_key
        ```

## Usage

1. **Run the Streamlit app**
    ```bash
    streamlit run app.py
    ```

2. **Interacting with the Chatbot**
    - Open your web browser and go to `http://localhost:8501`.
    - Enter your name and employee ID to start interacting with the chatbot.
    - Select the type of HR inquiry you need help with and ask your question.

## Customization

To customize the chatbot for your organization, you can modify the text files in the `base/` directory with your specific company policies, benefits, leave request processes, and payroll information.

### Adding More Assistants

To add more assistants, you can follow the structure in the `HrWebApp.py` file, defining new assistants with their respective instructions and vector store IDs.


