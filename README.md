# Q&A Bot with Gemini Pro LLM

## Overview

This project features a Q&A (Question and Answer) bot leveraging the capabilities of the powerful Gemini Pro Large Language Model (LLM). The bot is designed to provide answers based on both text and images. The backend is implemented in Python using the Gemini Pro LLM, and the frontend is developed using Streamlit. Additionally, there is a `vision.py` module that facilitates handling questions related to images.

## Features

- Text-based Q&A: The bot can answer questions posed in natural language.
- Image-based Q&A: The bot analyzes images and provides relevant responses to queries.
- User-friendly interface: The application is built using Streamlit, offering a simple and intuitive user interface.
- Gemini Pro LLM: Powered by the Gemini Pro Large Language Model for advanced natural language processing.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/qa-bot.git
2. Install the required dependencies:
  ```bash
   pip install -r requirements.txt
```
3. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```
   Open your web browser and navigate to http://localhost:8501 to use the Q&A bot.

## Usage

1. Enter your question in the text input field.
2. Click on the "Submit" button to get the bot's response.
3. If you have an image-related question, upload the image using the provided button.
4. The bot will process the question and display the relevant answer.

## Project Structure

- **app.py**: The Streamlit application for the Q&A bot's frontend.
- **vision.py**: Module for handling image-based questions.
- **requirements.txt**: Dependencies required for the project.

## Dependencies

- Streamlit
- Gemini Pro Large Language Model
- Other dependencies listed in `requirements.txt`

## Acknowledgments

This project makes use of the Gemini Pro Large Language Model, a powerful natural language processing tool.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Feel free to contribute to the project by submitting issues or pull requests!
