# Anveshak

Anveshak is a powerful, extensible AI assistant platform built on top of the **RedAmon** codebase, rebranded and enhanced for modern workflows. It provides:

- **Multi‑API‑Key support** – configure and switch between any number of LLM providers (OpenAI, Anthropic, Azure, local Ollama, etc.) directly from the Settings UI.
- **Multi‑Model selection** – each API key can expose one or more models; choose the model per request or let the system automatically pick the best one.
- **Dynamic MCP (Model‑Context‑Protocol) integration** – plug in external tools and services as MCP servers, extending the agent’s capabilities.
- **Premium UI/UX** – glass‑morphism styling, dark mode, smooth micro‑animations, and a polished design that looks great on a résumé.
- **Docker ready** – containerised for easy deployment, with environment variables pre‑configured for the new branding.

## Getting Started

```bash
# Clone the repository (already done for you)
# Navigate to the project directory
cd /Users/ayushkumar/Assignments/anveshak

# Install dependencies
npm install

# Run the development server
npm run dev
```

The app will be available at `http://localhost:3000`. Use the Settings page to add your LLM API keys and select models.

## Configuration

- **Environment variables** (see `.env.example`):
  - `ANVESHAK_VERSION` – the current version string.
  - `NEXT_PUBLIC_ANVESHAK_REPO` – URL of this GitHub repository.
- **API keys** are stored securely in the backend database; they are never exposed to the client.

## Contributing

Feel free to open issues or submit pull requests. Follow the existing code style and run `npm run lint` before submitting changes.

## License

MIT © 2024‑2026 Anveshak Contributors
