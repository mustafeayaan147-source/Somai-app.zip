# SomAI

SomAI is a mobile-friendly AI chat prototype using OpenRouter's OpenAI-compatible API.

## Deploy on Vercel
1. Upload this folder to a GitHub repository.
2. Import the repository into Vercel.
3. In Vercel Project Settings -> Environment Variables, add:
   - Name: OPENROUTER_API_KEY
   - Value: your OpenRouter secret key
4. Redeploy.
5. Open the Vercel URL on your phone.

Never put the API key inside `public/index.html` or send it to anyone in chat.

The backend uses model `openrouter/free`.
