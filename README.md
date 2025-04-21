

This is a simple Python desktop application built using Tkinter that allows users to interact with OpenAI's API. Users can enter a prompt, submit it, and receive a generated text response.

---

Features
- Easy-to-use graphical interface
- Prompt input and output display areas
- Uses the OpenAI Completion API
- Secure API key handling via `.env` file

---

Requirements
Make sure you have the following Python packages installed:

```bash
pip install openai python-dotenv
```

---
 Setup `.env` File
To keep your API key secure, store it in a `.env` file.

1. In the same directory as your script, create a file named `.env`
2. Add the following line (replace with your actual API key):

```
OPENAI_API_KEY=your_openai_api_key_here
```
 Do not use quotes around the key, and avoid spaces around the `=`.

 Never Upload Your `.env` File
- Add `.env` to your `.gitignore` to prevent it from being uploaded to GitHub.
- Create

