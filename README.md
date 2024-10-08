# Jarvis - Your Personal Assistant

**Jarvis** is a versatile personal assistant application built using Python. It provides various functionalities including weather updates, task management, reminders, system status checks, and more. The assistant can be interacted with via text commands in the terminal.

## Features

- **Weather Information**: Get current weather details including temperature, weather conditions, and precipitation for various cities.
- **Task Management**: Add, list, and mark tasks as completed.
- **Reminders**: Set daily reminders and get notifications.
- **System Status**: Check basic system information such as CPU, RAM, and OS details.
- **Calculations**: Perform basic arithmetic calculations.
- **Web Search**: Perform web searches and get Google search URLs.
- **News**: Fetch the latest news headlines.
- **Jokes**: Get random jokes to lighten your mood.
- **Definitions**: Fetch word definitions from an online dictionary.
- **Unit Conversions**: Convert between various units like kilometers to miles, Celsius to Fahrenheit, etc.
- **Summaries**: Get concise summaries of terms from Wikipedia.

## Installation

1. **Clone the Repository**

    ```bash
    git clone https://github.com/yourusername/jarvis.git
    cd jarvis
    ```

2. **Create a Virtual Environment (optional but recommended)**

    ```bash
    python -m venv venv
    source venv/bin/activate   # On Windows use `venv\Scripts\activate`
    ```

3. **Install Required Packages**

    ```bash
    pip install -r requirements.txt
    ```

4. **Obtain API Keys**

    - **News API**: Sign up at [News API](https://newsapi.org/) and replace the `api_key` in the `get_news` function with your API key.

## Usage

1. **Run the Application**

    ```bash
    python jarvis.py
    ```

2. **Interact with Jarvis**

    Type your commands in the terminal. For example:
    - `weather in London`
    - `add task Buy groceries`
    - `complete task Buy groceries`
    - `reminder Meeting at 3 PM`
    - `calculate 5 plus 3`
    - `search Python programming`
    - `news`
    - `define Python`
    - `convert 5 km to miles`

## Command Reference

- **Weather**: `weather in [city]`
- **Task Management**: `add task [task]`, `list tasks`, `complete task [task]`
- **Reminder**: `reminder [reminder]`
- **System Status**: `system status`
- **Calculation**: `calculate [expression]`
- **Web Search**: `search [query]`
- **News**: `news`
- **Jokes**: `joke`
- **Definition**: `define [word]`
- **Unit Conversion**: `convert [amount] [unit] to [unit]`
- **Summary**: `what is [term]`, `who is [term]`

## File Structure

- `jarvis.py`: Main script for running the assistant.
- `tasks.txt`: File where tasks are stored.
- `requirements.txt`: List of Python packages required for the project.

## Troubleshooting

- **API Errors**: Ensure you have valid API keys and that your internet connection is stable.
- **Package Installation Issues**: Make sure you have all necessary permissions and the correct Python version.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [pyttsx3](https://pypi.org/project/pyttsx3/): For text-to-speech functionality.
- [requests](https://pypi.org/project/requests/): For making HTTP requests.
- [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/): For parsing HTML.

