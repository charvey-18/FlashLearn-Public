# FlashLearn - AI-Powered Flashcards

Create and study flashcards on any topic with AI assistance. Features text-to-speech for hands-free learning.

🔗 **[Live Demo](https://charvey-18.github.io/FlashLearn-Public/)**

## Features

- ✨ **AI-Powered Generation** - Create flashcards on any topic using GPT-4
- 🎧 **Hands-Free Learning** - Text-to-speech reads cards aloud with headphone controls
- ☁️ **Cloud Sync** - Sign in to save your decks across devices (Supabase)
- ✏️ **Full Editing** - Edit any card's question, answer, or source
- ⭐ **Favorites & Progress** - Track mastery and bookmark cards for review
- 🔀 **Shuffle Mode** - Randomize card order for better retention
- 🌙 **Dark Theme** - Easy on the eyes

## Pre-loaded Decks

Start learning immediately with these interview prep decks:

| Deck | Cards | Description |
|------|-------|-------------|
| 🏦 LBO Modeling | 14 | Leveraged buyout fundamentals, deal structure, returns |
| 💰 DCF Valuation | 12 | Discounted cash flow, WACC, terminal value |
| 📒 Accounting | 12 | Financial statements, ratios, key concepts |

## How to Use

### Study Pre-loaded Decks
1. Open the app
2. Click any deck to start studying
3. Tap cards to flip between question and answer
4. Use play button for auto-read mode with TTS
5. Mark cards as "Mastered" or "Still Learning"

### Create Custom Decks with AI
1. Click "Sign In" and create an account
2. Click "Set up OpenAI API Key" and enter your key
3. Click "Create Deck with AI"
4. Enter any topic (e.g., "Python data structures", "World War 2")
5. Review and edit generated cards
6. Save your deck

### Get an OpenAI API Key
1. Go to [platform.openai.com/api-keys](https://platform.openai.com/api-keys)
2. Create an account or sign in
3. Generate a new API key
4. Copy and paste it into FlashLearn

> Your API key is stored locally in your browser and never sent to our servers.

## Tech Stack

- **Frontend**: React 18 (CDN, single-file)
- **AI**: OpenAI GPT-4o-mini
- **Backend**: Supabase (Auth + PostgreSQL)
- **TTS**: Web Speech Synthesis API
- **Hosting**: GitHub Pages

## Development

This is a single-file React app with no build step required. Simply:

1. Clone the repo
2. Open `index.html` in a browser
3. For Supabase features, set up your own project at [supabase.com](https://supabase.com)

## License

MIT
