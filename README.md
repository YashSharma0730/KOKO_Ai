KOKO Ai - Your Compassionate Mental Health Companion



KOKO Ai is an AI-powered chatbot designed to provide compassionate and supportive mental health assistance. Built using Streamlit and Cohere, it offers uplifting advice, self-care tips, and encouragement to users in distress.

Features

Empathetic Responses: Uses a warm and reassuring tone to support users.

Keyword-based Advice: Fetches relevant mental health advice from a dataset.

Real-time Interaction: Engaging chat interface built with Streamlit.


Tech Stack

Python (Streamlit, JSON, Cohere API)

LangChain Community (Cohere LLM integration)

Frontend Styling (Custom Streamlit CSS)

Installation Prerequisites

Python 3.8+

Streamlit

Cohere API Key

Steps

Clone this repository:

git clone https://github.com/YashSharma0730/KOKO_Ai.git
cd KOKO-Ai

Create a virtual environment and install dependencies:

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt

Add your Cohere API Key to the script (COHERE_API_KEY variable).

Run the chatbot:

streamlit run app.py

Usage

Start the chatbot using Streamlit.

Interact with KOKO Ai by typing messages in the input field.

Receive responses with mental health support and advice.

Click "Clear Chat" to reset the conversation.

Project Structure

KOKO-Ai/
│── app.py                   # Main Streamlit app
│── requirements.txt         # Dependencies
│── Instances.json           # Mental health dataset
│── Screenshot.png           # UI preview
└── README.md                # Documentation

Contribution

Contributions are welcome! Feel free to fork this repository and submit pull requests.

License

This project is licensed under the MIT License.

Acknowledgments

Cohere for NLP capabilities

Streamlit for an interactive UI

