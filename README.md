# InterviewChat

A Streamlit-based chatbot application for simulating job interviews. Users can input their personal information, select a position and company, and engage in a conversational interview with an AI-powered HR executive. After the interview, the app provides feedback on the user's performance.

## Features

- **Personal Information Collection**: Gather user details like name, age, experience, and skills.
- **Position and Company Selection**: Choose from predefined levels (Junior, Mid, Senior), positions (Data Scientist, Software Engineer, Product Manager), and companies (Meta, Google, Amazon, Microsoft, Apple, LinkedIn).
- **Interactive Interview**: Conduct a simulated interview with up to 5 user responses, powered by OpenAI's GPT-4o model.
- **Feedback System**: Receive a score and detailed feedback after the interview.
- **Restart Functionality**: Easily restart the interview process.

## Installation

1. Clone or download the repository.
2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Set up your OpenAI API key:
   - Create a `.streamlit/secrets.toml` file in the project root.
   - Add your OpenAI API key:
     ```
     OPENAI_API_KEY = "your-api-key-here"
     ```

## Usage

1. Run the Streamlit app:
   ```
   streamlit run app.py
   ```
2. Open the provided URL in your browser.
3. Follow the on-screen instructions to complete the setup and start the interview.
4. Engage in the chat by responding to the AI's questions.
5. After 5 responses, click "Get Feedback" to view your performance evaluation.
6. Use the "Restart Interview" button to start over.

## Requirements

- Python 3.7+
- OpenAI API key
- Dependencies listed in `requirements.txt`:
  - streamlit
  - openai
  - streamlit-js-eval

## Troubleshooting

- **Import Errors**: Ensure all dependencies are installed via `pip install -r requirements.txt`.
- **API Key Issues**: Verify that your OpenAI API key is correctly set in `.streamlit/secrets.toml`.
- **App Not Starting**: Check for any missing environment variables or configuration issues.
- **Streamlit Errors**: Make sure Streamlit is installed and up to date.

## License

This project is for educational purposes. Please ensure compliance with OpenAI's usage policies.