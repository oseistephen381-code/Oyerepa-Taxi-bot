# Ghana AI — Real multilingual version

This version upgrades the original demo into a real AI web app.

## What it includes
- Real AI responses through a server-side API route
- English, Twi, Fante, Ga, Ewe, Dagbani, Dagaare, Gonja, Nzema, Kasem and Hausa modes
- Chat, translation and teaching modes
- Conversation history
- Browser voice input where supported
- Mobile-friendly UI
- API key kept on the server instead of in browser JavaScript
- Demo mode so you can try the interface before adding an API key

## Run locally
1. Install Node.js 20+.
2. Copy `.env.example` to `.env`.
3. Put your API key in `.env` when you are ready for live AI.
4. Run:
   npm install
   npm start
5. Open:
   http://localhost:3000

## Important
Do not put your API key inside `app.js` or `index.html`. Keep it in `.env` on the server/hosting provider.

For production hosting, use a service that supports a Node.js server or serverless API routes. A static-only host cannot safely keep the API key in browser code.
