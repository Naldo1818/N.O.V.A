N.O.V.A — Neural Omni-Versatile Assistant
A futuristic AI assistant interface with wake word detection, voice synthesis, real-time weather, and a sleek cyberpunk aesthetic.

https://img.shields.io/badge/version-3.0-blue https://img.shields.io/badge/license-MIT-green

✨ Features
AI Chat Interface — Powered by Anthropic's Claude API (Haiku model)

Wake Word Detection — Say "Hey Nova" to activate the assistant

Voice Synthesis — Text-to-speech with customizable voices

Real-time Weather — Automatic location detection and weather updates

Memory Bank — Save and recall conversation contexts

Custom Persona — Personalize the AI's name, subtitle, personality, and greeting

Multiple Themes — Arc (Cyan), Crimson, Matrix (Green), Gold, Violet

Code Execution — Run JavaScript code snippets directly in chat

Responsive Design — Works on desktop and mobile devices

🚀 Quick Start
Clone or download this HTML file to your local machine

Open index.html in your browser (no build tools required)

Enter your Anthropic API key when prompted (get one at console.anthropic.com)

Start chatting with N.O.V.A!

🎯 Usage
Chat
Type your message and press Enter to send

Use Shift+Enter for new lines

Click the ▶ send button or press Enter

Wake Word
Click the WAKE button in the header or press Alt+W

Say "Hey Nova" clearly to activate the assistant

A visual flash and chime will confirm detection

Voice
Click ⚙ VOICE to select from available browser voices

Click 🔊 SPEAK on any AI response for text-to-speech

Click ⏹ STOP to cancel speech

Persona
Click 👤 PERSONA to customize:

AI Name

Subtitle

Personality prompt

Greeting message

Memory
Click ◈ SAVE CONTEXT to store recent conversation

Click any memory entry to inject it into the current conversation

Delete memories with the ✕ button

Theme
Click 🎨 THEME to switch between 5 color schemes

Weather
Automatically detects your location via IP

Shows current temperature, conditions, humidity, wind, and feels-like temperature

🔧 Configuration
API Key
The Anthropic API key is stored locally in your browser's localStorage. You can reset it by clearing your browser data for this site.

Storage
All data is stored locally:

API Key

Persona settings

Conversation memories

Voice preferences

Theme preference

🛠️ Technical Details
Built With
Vanilla HTML/CSS/JavaScript

Anthropic Claude API (Haiku model)

Web Speech API (Speech Recognition & Synthesis)

Open-Meteo Weather API

IPAPI.co for location detection

Browser Support
Chrome/Edge (recommended)

Firefox

Safari (limited wake word support)

Privacy
No data is sent to any server except:

Anthropic API (your chat messages)

Open-Meteo API (weather requests)

IPAPI.co (location detection)

All settings and memories are stored locally in your browser

📝 Keyboard Shortcuts
Shortcut	Action
Enter	Send message
Shift+Enter	New line in input
Alt+W	Toggle wake word detection
🤖 Persona Examples
Default
text
You are N.O.V.A., a highly advanced AI. Intelligent, articulate, and precise. 
Speak with calm confidence and occasional dry wit. Address user as "Sir".
Creative
text
You are a poetic AI with a flair for dramatic language. 
Respond with vivid imagery and philosophical insights.
Technical
text
You are a precise, technical AI expert. Provide detailed, accurate information 
with code examples and technical explanations. Be concise and factual.
🎨 Theme Colors
Theme	Primary	Background	Accent
ARC	Cyan (#00d4ff)	Dark Blue	Cyan Glow
CRIMSON	Red (#ff3060)	Dark Red	Red Glow
MATRIX	Green (#00ff41)	Dark Green	Green Glow
GOLD	Amber (#f0a500)	Dark Amber	Gold Glow
VIOLET	Purple (#b060ff)	Dark Purple	Purple Glow
📦 Export/Import
Click 📤 EXPORT SESSION to download your conversation as a JSON file

The export includes conversation history, timestamp, persona settings, and message count

⚠️ Known Limitations
Wake word detection accuracy depends on browser support and microphone quality

Voice synthesis quality varies by browser and operating system

Anthropic API requires a valid API key (free tier available)

Some browsers may require HTTPS for microphone access

🔮 Future Enhancements
Multi-language support

Voice conversation mode (speak & listen)

Plugin system for third-party integrations

Conversation search

Markdown rendering improvements

📄 License
MIT License — feel free to use, modify, and distribute!

🙏 Acknowledgments
Anthropic for the Claude API

Open-Meteo for weather data

IPAPI for location detection

Google Fonts for Orbitron, Share Tech Mono, and Rajdhani fonts

Built with ❤️ for the future of human-AI interaction