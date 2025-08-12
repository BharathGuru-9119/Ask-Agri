# Ask Agri Expert

Ask Agri Expert is a conversational AI web application designed to assist farmers and agricultural enthusiasts. It allows users to ask crop-related questions, get expert-like responses, and interact in a chat-style interface. The app supports light/dark themes, persistent chat history, and integrates with the Google Gemini API for generating answers.

## Features

- 💬 AI-powered chat using Google Gemini API
- 🌗 Dark mode / Light mode toggle
- 💾 Persistent chat history stored in local storage
- 🗑 Clear chat history with one click
- 📋 Copy response feature
- 📱 Responsive design for mobile and desktop
- ⌨️ Typing effect for incoming AI messages

## Demo

![Ask Agri Expert Screenshot]
<img width="1626" height="906" alt="Screenshot 2025-08-12 094544" src="https://github.com/user-attachments/assets/6237b603-85e6-41bd-93ed-2dadd57bf4c1" />



## Tech Stack

- Frontend: HTML, CSS, JavaScript
- API: Google Generative Language API (Gemini 1.5 Flash)
- Icons: Google Material Symbols
- Fonts: Google Fonts (Poppins)
- Storage: Browser Local Storage

## Getting Started

### Prerequisites

- Node.js (optional if running with local server)
- Google Generative Language API key

### Installation

1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/ask-agri-expert.git
   cd ask-agri-expert
   ```

2. Set up your API Key:  
   Open `script.js` and replace:
   ```javascript
   const API_KEY = "your_google_gemini_api_key";
   ```

3. Run locally:  
   - Open `index.html` directly in your browser  
   **or**
   - Serve with a local server:
     ```bash
     npx serve .
     ```
     Then visit [http://localhost:3000](http://localhost:3000).

## Project Structure

```
.
├── index.html        # Main HTML page
├── style.css         # Styling for the app
├── script.js         # App logic and API integration
├── images/           # Avatars/icons
├── .env              # (optional) API key storage
└── README.md         # Documentation
```

## Usage

- Type your question in the input box.
- Press Enter or click the send icon.
- Wait for AI to respond with typing effect.
- Toggle light/dark mode with the theme icon.
- Clear chat history with the delete icon.
- Copy any response by clicking the copy icon.

## Environment Variables (Optional)

```ini
REACT_APP_GEMINI_API_KEY=your_api_key_here
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Google Gemini API for AI-generated answers
- Google Fonts for Poppins
- Material Symbols for icons

