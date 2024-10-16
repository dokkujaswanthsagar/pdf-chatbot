Here’s the content formatted for a GitHub README file:

---

# PDF Chatbot using Google Generative AI and Streamlit

This project provides a *PDF Chatbot* that enables users to upload PDF documents and interact with the contents using a chatbot interface. The chatbot is powered by *Google Generative AI* (Gemini 1.5 Pro model) and built using *Streamlit* for a seamless, interactive user experience.

## Features

- *PDF Upload and Interaction*: Users can upload PDFs and ask questions about the document.
- *Real-time Chat*: Leverages the Gemini 1.5 Pro model to generate accurate responses to queries about the uploaded document.
- *Chat History*: Users can view all previous questions and answers, with an option to clear the history.
- *Simple UI*: Clean, stylish interface with custom design elements like a dark background and centered headers.

## Prerequisites

- *Python 3.x*
- A *Google Cloud API key* to access the Google Generative AI model.
- *Streamlit* installed for running the web app.

## Setup

1. Clone this repository:

    bash
    git clone https://github.com/your-repository/pdf-chatbot.git
    cd pdf-chatbot
    

2. Install dependencies:

    bash
    pip install -r requirements.txt
    

3. Create a .env file in the root directory to securely store the API key:

    bash
    touch .env
    

    Add your API key in this format:

    
    GOOGLE_API_KEY = "YOUR_GOOGLE_API_KEY"
    

4. Set the API key in your environment:

    bash
    setx GOOGLE_API_KEY "YOUR_GOOGLE_API_KEY"
    

5. Run the Streamlit app:

    bash
    streamlit run app.py
    

6. Access the app on your browser at http://localhost:8501.

## Usage

1. *Upload a PDF*: Use the sidebar to upload a PDF document.
2. *Ask a Question*: Input your query into the chatbox. The chatbot will respond based on the contents of the PDF.
3. *Chat History*: All interactions are displayed in the "Chat History" section, with an option to clear the history.
4. *Save Conversations*: Chat history is saved automatically in a file named chat_history.txt.

## Example

- Upload sample.pdf.
- Ask questions like "What is the main topic of the document?" or "Summarize section 2."
- The chatbot will analyze the PDF and provide relevant answers.

## Project Structure


.
├── app.py                 # Main app file
├── .env                   # Environment file for API key
├── requirements.txt        # List of dependencies
└── chat_history.txt        # Generated chat history file


## Technologies

- *Google Generative AI (Gemini 1.5 Pro)*: The AI model used for generating responses.
- *Streamlit*: Framework for building the user interface.
- *Python*: The programming language used for backend logic.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Let me know if you need further changes or additional details!
