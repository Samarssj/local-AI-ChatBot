# Local AI ChatBot

A simple working chatbot that runs fully in the browser. It uses HTML, CSS, and JavaScript only, so there is no backend, no install step, and no API key required.

## Features

- Clean responsive chat interface
- Quick prompt buttons
- Enter-to-send support
- Typing indicator
- Local chat history with `localStorage`
- Rule-based reply logic for common intents like planning, email drafts, study tips, summaries, and general help

## How to Run

Open this file in your browser:

```text
outputs/index.html
```

You can also run a local static server from the project folder:

```bash
python3 -m http.server 4173 --directory outputs
```

Then visit:

```text
http://localhost:4173
```

## How It Works

The chatbot is powered by JavaScript inside `outputs/index.html`. It checks the user's message for keywords and returns a matching response. For example, if the message contains words like `plan`, `schedule`, or `day`, it returns a simple daily plan.

This means the chatbot is private and fast, but it is not connected to a real language model. To make it a true AI chatbot, you would connect the frontend to an LLM API or a local model service.

## Screenshot

<img width="1280" height="720" alt="chatbot-screenshot" src="https://github.com/user-attachments/assets/6d8fa383-9d64-4937-9196-3924299694d7" />

