# FlashLearn - AI-Powered Study App

A comprehensive flashcard app for studying any topic. Features GCSE revision content, AI-powered card generation, and hands-free learning with text-to-speech.

**[Live Demo](https://charvey-18.github.io/FlashLearn-Public/)**

## Features

- **Hierarchical Folders** - Organised subject structure with nested folders
- **AI-Powered Generation** - Create flashcards on any topic using GPT-4
- **Hands-Free Learning** - Text-to-speech reads cards aloud
- **Quiz Mode** - Timed quizzes with scoring
- **Study Streaks** - Track daily progress and maintain streaks
- **Exam Countdown** - Set exam dates and see days remaining
- **Cloud Sync** - Sign in to save custom decks across devices
- **Progress Tracking** - Mark cards as mastered or still learning
- **Favorites** - Bookmark cards for focused review

## Pre-loaded Content

### GCSE Revision (~200+ cards)

| Subject | Topics |
|---------|--------|
| **Mathematics** | Number, Algebra, Geometry, Statistics & Probability |
| **Biology** | Cells, Organisation, Infection, Bioenergetics, Homeostasis, Inheritance, Ecology |
| **Chemistry** | Atomic Structure, Bonding, Quantitative, Chemical Changes, Energy, Rates, Organic, Analysis, Atmosphere |
| **Physics** | Energy, Electricity, Particles, Atomic Structure, Forces, Waves, Magnetism, Space |
| **English Literature** | Macbeth, An Inspector Calls, A Christmas Carol, Romeo & Juliet, Poetry Anthology |
| **English Language** | Reading Skills, Writing Techniques, Grammar, Literary Devices |
| **History** | Elizabethan England, Nazi Germany, Medicine Through Time, Cold War |
| **Design & Technology** | Materials, Processes, Systems |

### Finance & Business

| Topic | Description |
|-------|-------------|
| LBO Modeling | Leveraged buyouts, deal structure, returns |
| DCF Valuation | Discounted cash flow, WACC, terminal value |
| Accounting | Financial statements, ratios, key concepts |

## How to Use

### Study Pre-loaded Content
1. Open the app and browse folders
2. Click any deck to start studying
3. Tap cards to flip between question and answer
4. Mark cards as "Got It" or "Still Learning"
5. Use the play button for hands-free TTS mode

### Take a Quiz
1. Open any deck
2. Click "Quiz" in the top right
3. Answer within 30 seconds per question
4. See your score at the end

### Track Exams
1. Click "Exams" on the home screen
2. Add your exam dates
3. See countdown with colour-coded urgency

### Create Custom Decks with AI
1. Sign in or create an account
2. Enter your OpenAI API key (get one at [platform.openai.com](https://platform.openai.com/api-keys))
3. Click "Create with AI"
4. Enter any topic
5. Review and save your deck

## Tech Stack

- **Frontend**: React 18 (CDN, single-file)
- **AI**: OpenAI GPT-4o-mini
- **Backend**: Supabase (Auth + PostgreSQL)
- **TTS**: Web Speech Synthesis API
- **Storage**: localStorage for progress, Supabase for custom decks
- **Hosting**: GitHub Pages

## Development

Single-file React app with no build step:

1. Clone the repo
2. Open `index.html` in a browser
3. For cloud features, set up Supabase at [supabase.com](https://supabase.com)

## License

MIT
