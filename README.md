# AI Chat Assistant

This project is a Streamlit-based web application that provides an AI-powered chat interface using OpenAI's API.

## Features

- Interactive chat interface
- Integration with OpenAI's API
- Session management for continuous conversations
- Custom CSS for improved user experience

## File Structure

- `app-streamlit.py`: Main Streamlit application file
- `utils/`:
  - `openai_utils.py`: Utility functions for OpenAI API interactions
  - `message_utils.py`: Message handling utilities
  - `custom_css_main_page.py`: Custom CSS for the main page
  - `custom_css_banner.py`: Custom CSS for the banner
- `.streamlit/config.toml`: Streamlit configuration file
- `.gitignore`: Git ignore file

## Setup

1. Clone the repository
2. Install the required dependencies:
   ```sh
   pip install streamlit openai
   ```
3. Set up your OpenAI API key in Streamlit secrets

## Running the Application

To run the application, use the following command:

```
streamlit run app-streamlit.py