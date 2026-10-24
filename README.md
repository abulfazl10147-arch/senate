# Senate

**A council of artificial intelligences.**

Senate puts several AI advisors in one room. Give each a point of view, ask a question, and watch them debate it so the trade-offs are easier to see before you decide.

It is a single HTML file with no server. You bring your own API keys, and everything stays in your browser.

## Features

- Advisors with their own name, API key, and role (point of view)
- Group-chat debate with streaming replies, in rounds you can steer
- Saved POV library with a starter pack, plus shared ground rules for every advisor
- Image attachments, so advisors can critique a logo, mockup, or screenshot
- Final votes with confidence scores, a neutral summary, and a joint answer from all advisors
- Saved debates and Markdown export
- Works with Google (Gemini), OpenAI, Anthropic, and OpenRouter keys
- Light and dark themes

## Use it

- **Online:** *(add your link here once it is live)*
- **Locally:** download `index.html` and open it in your browser. If a provider blocks the request, run `python -m http.server` in the folder and open `localhost:8000`.

## Getting started

1. Get an API key from a provider (Google AI Studio has a free tier).
2. Open **Settings** and add two or more advisors: a name, your key, and a role.
3. Go **Home**, press **Start a debate**, and enter a topic.

The default model for each provider may go out of date. If you see a "model not found" error, type a current model name into that advisor's **Model** box.

## Privacy

- No server, no accounts, no analytics.
- Keys, advisors, POVs, and saved debates live in your browser's local storage. **Clear all data** in Settings erases them.
- Debate content goes straight from your browser to the AI provider you chose, under that provider's terms. Free tiers may use it to improve their products.
- Set a spending limit on your keys, and revoke any key you used on a shared computer.

## Disclaimer

Senate is an independent project, not affiliated with Anthropic, Google, OpenAI, or OpenRouter. AI output can be wrong; it is not professional advice. You are responsible for costs on your own API keys.

## License

MIT (see `LICENSE`).
