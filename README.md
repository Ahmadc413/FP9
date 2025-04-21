OpenAI Text Completion GUI

This is a simple Python desktop application built using Tkinter that allows users to interact with OpenAI's API. Users can enter a prompt, submit it, and receive a generated text response.

🚀 Features

Easy-to-use graphical interface

Prompt input and output display areas

Uses the OpenAI Completion API

Secure API key handling via .env file

📦 Requirements

Make sure you have the following Python packages installed:

pip install openai python-dotenv

🔐 Setup .env File

To keep your API key secure, store it in a .env file.

In the same directory as your script, create a file named .env

Add the following line (replace with your actual API key):

OPENAI_API_KEY=your_openai_api_key_here

⚠️ Do not use quotes around the key, and avoid spaces around the =.

🧠 How It Works

The .env file is loaded using the python-dotenv package.

The API key is retrieved and used to make requests to OpenAI.

A Tkinter GUI allows users to enter a prompt and receive generated completions.

▶️ Running the App

Run the Python script from your terminal:

python openai_gui.py

Once running:

Type your prompt into the top box

Click the Submit button

View the response in the bottom box

🛠 Customization

You can switch the model in the script by changing the engine value in openai.Completion.create() (e.g., use "gpt-3.5-turbo-instruct" for faster responses)

Adjust max_tokens, temperature, and other parameters to fit your use case

