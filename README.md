# AI Bot Clone

Chatbot clone developed with Node.js and Express.js, mimicking ChatGPT, as a learning project for testing web development and AI API integration.

## Features

- **Backend**: Express.js server handling POST requests for user input.
- **Frontend**: Basic HTML/JavaScript app for sending the prompt and receiving responses.
- **APIs Tested**: Had tried out the OpenAI, Grok, DeepSeek, and Hugging Face APIs.
- **Tools**: Used `dotenv` for environment variables and Git version control.

## Status

- **Complete**: Backend, frontend, and API integration logic fully completed.
- **Challenge**: No API responses because billing needs (OpenAI, Grok, DeepSeek) or rate limits (Hugging Face) weren't met. Local model (Ollama) tried but hardware (low RAM) wasn't sufficient.
- **Outcome**: Functional app structure showing Node.js, Express, and API processing, although without live AI responses.

## Lessons Learned

- Installing and debugging REST APIs with Express.js.
- Using environment variables with `dotenv`.
- GitHub version control and workflow.
- Collaboration with free-tier API restrictions and hardware problems.

## Dependencies

- `express`: Backend server framework.
- `cors`: Enable cross-origin requests.
- `dotenv`: Environment variable management.

## Next Steps

- Return with improved hardware (8GB+ RAM) to support running Ollama locally.
- Research new free AI APIs that do not charge.
- Enhance frontend with better UI/UX.

## How to Run

1. Clone the repo: `git clone https://github.com/your-username/ai-bot-clone.git`
2. Install dependencies: `npm install`
3. Start `.env` with an API key (if there is one available).
4. Start server: `node server.js`
5. View `index.html` or via app like `live-server`.

_Note_: API responses require a valid, free-tier API key, which was not possible due to billing limits.

---

Developed by [Sunayan Duwal]
