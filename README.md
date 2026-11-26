# AI Meeting Notes Extractor

A browser-based meeting notes analysis dashboard built with Python notebook display components and JavaScript.

## Features

- Premium dark dashboard interface
- Offline, keyword-based action-item extraction
- Gemini 3 Flash analysis mode
- Meeting summary, action items, owners, deadlines, priority, status, and decisions
- Task analytics and session-only meeting history
- Export reports as TXT and CSV, or print/save as PDF

## Run

1. Open `AI_Meeting_Notes_Extractor.ipynb` in JupyterLab or a compatible notebook environment.
2. Run the app code cell.
3. Paste meeting notes into the app.
4. Choose Offline mode, or choose Gemini mode and enter your Gemini API key in the password field.
5. Click **Analyze Meeting Notes**.

## API key safety

The notebook does not contain a saved Gemini API key. Enter the key in the app only when you choose Gemini mode. Never commit API keys, passwords, or other secrets to GitHub. If a key was previously exposed in a public repository, revoke it and create a new one.

## Notes

- Offline mode uses simple keyword rules; its output may need manual review.
- Gemini mode requires an internet connection and a valid Google Gemini API key.
- Meeting history is kept only in the current browser session and is not saved to a database.
