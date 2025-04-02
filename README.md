# Custom Recipe Tutorial Generator

This project is a Flask-based web application that generates recipe tutorials based on user-inputted ingredients. It utilizes OpenAI's GPT-3.5 to suggest recipes, including a fun name, a humorous version of the name, step-by-step instructions, and a fun fact at the end.

## Features
- Enter a list of ingredients to receive a custom recipe.
- Automatically generates a creative and fun recipe name.
- Provides step-by-step cooking instructions.
- Displays a fun fact related to the recipe.
- Simple web interface built with Flask and Bootstrap.
- Copy recipe output to clipboard with a single click.

## Prerequisites
Before running this project, ensure you have the following installed:
- Python 3.x
- Flask
- OpenAI API access and API key

## Installation
1. Clone this repository:
   ```sh
   git clone https://github.com/your-username/your-repository.git
   cd your-repository
   ```

2. Install dependencies:
   ```sh
   pip install flask boltiotai
   ```

3. Set up your OpenAI API key as an environment variable:
   ```sh
   export OPENAI_API_KEY='your-api-key-here'  # Linux/macOS
   set OPENAI_API_KEY='your-api-key-here'  # Windows (Command Prompt)
   ```

## Usage
1. Run the Flask application:
   ```sh
   python main.py
   ```
2. Open a web browser and go to:
   ```
   http://localhost:8080/
   ```
3. Enter ingredients and get a recipe tutorial!

## API Endpoints
- `/` - Main page with form input.
- `/generate` - Backend API endpoint that processes user input and returns a recipe.

## Deployment
To deploy this project on a cloud server:
- Use services like AWS, Heroku, or Render.
- Set the `OPENAI_API_KEY` in the server environment.
- Ensure Flask is running on a public-facing IP.

## License
This project is open-source and available under the [MIT License](LICENSE).

## Acknowledgments
- Powered by [OpenAI](https://openai.com/)
- Flask framework for web development
- Bootstrap for styling

