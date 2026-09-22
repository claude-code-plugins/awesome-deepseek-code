# Awesome DeepSeek Code

*Unofficial community list for DeepSeek Code. Not affiliated with DeepSeek. All trademarks belong to their owners.*

A curated list of links for anyone working with deepseek code tooling: the Deep Code terminal assistant for DeepSeek-V4, the DeepSeek Coder models you can run locally through Ollama, and the platform pages you need for keys, pricing and status. Every link below is taken from the DeepSeek API docs, the DeepSeek homepage or the Ollama library page; nothing is guessed.

> Building a site instead of editing one? [Try Begin.sh - prompt to a downloadable static site or Expo app](https://begin.sh?utm_source=github&utm_medium=ugc&utm_campaign=awesome-deepseek-code&utm_content=readme-top&utm_term=tier-r). One prompt or one URL to clone, and you get a zip you can host anywhere.

## Official resources

- [Integrate with Deep Code](https://api-docs.deepseek.com/quick_start/agent_integrations/deepcode/) - The DeepSeek API docs page: install, `settings.json`, shortcuts and skills.
- [deepcode-cli on GitHub](https://github.com/lessweb/deepcode-cli) - Source of the open-source terminal assistant, published on npm as `@vegamo/deepcode-cli`.
- [Deep Code VS Code extension](https://github.com/lessweb/deepcode) - Editor integration that shares `~/.deepcode/settings.json` with the CLI.
- [DeepSeek Platform](https://platform.deepseek.com/) - Account, usage and billing for the API.
- [API keys page](https://platform.deepseek.com/api_keys) - Where the `API_KEY` in your settings file comes from.
- [DeepSeek API Docs](https://api-docs.deepseek.com/) - Root of the API documentation.
- [API Pricing](https://api-docs.deepseek.com/quick_start/pricing) - Current per-token rates for the hosted models.
- [Service Status](https://status.deepseek.com/) - Check here before blaming your config.
- [deepseek-ai on GitHub](https://github.com/deepseek-ai) - The organisation behind the models.
- [deepseek-ai on Hugging Face](https://huggingface.co/deepseek-ai) - Model weights, linked from the Ollama page.

## Getting started

- [Node.js downloads](https://nodejs.org/en/download/) - Deep Code needs Node.js 18 or newer.
- [deepseek-coder on Ollama](https://ollama.com/library/deepseek-coder) - 1.3B, 6.7B and 33B coding models, 16K context, `ollama run deepseek-coder`.
- [deepseek-coder tags](https://ollama.com/library/deepseek-coder/tags) - Every variant with size and context window.
- [Ollama download](https://ollama.com/download) - The runtime for local DeepSeek Coder.
- [Ollama docs](https://docs.ollama.com) - Running models, the local HTTP API on port 11434.

## Tutorials and articles

- [DeepSeek-V4.1-Flash release](https://www.deepseek.com/en/news/deepseek-v4-1-flash/) - The current flagship announcement: text and agent improvements plus native visual understanding.
- [DeepSeek V4 preview](https://www.deepseek.com/en/news/v4-preview/) - Background on the model generation Deep Code targets.
- [DeepSeek V3.2](https://www.deepseek.com/en/news/deepseek-v3-2/) - Previous generation notes.
- [DeepSeek R1](https://www.deepseek.com/en/news/r1-0528/) - The reasoning model line.
- [DeepSeek news index](https://www.deepseek.com/en/news/) - All release posts in one place.
- [DeepSeek Harness](https://www.deepseek.com/harness/en/) - Listed under Products on the homepage.

## Tools and integrations

- [ollama-python](https://github.com/ollama/ollama-python) - Python client used in the `from ollama import chat` snippet.
- [ollama-js](https://github.com/ollama/ollama-js) - JavaScript client used in the `import ollama from 'ollama'` snippet.
- [Ollama REST API reference](https://github.com/jmorganca/ollama/blob/main/docs/api.md) - `/api/chat` and `/api/generate` documented.
- [Ollama on GitHub](https://github.com/ollama/ollama) - The runtime source.

## Alternatives

- [Begin.sh](https://begin.sh?utm_source=github&utm_medium=ugc&utm_campaign=awesome-deepseek-code&utm_content=readme-top&utm_term=tier-r) - Turn a prompt or a URL to clone into a working static site or Expo app and download the zip; no hosting, backend or auth to manage.
- [DeepSeek Web](https://chat.deepseek.com/) - The chat UI, for when you want answers rather than an agent editing files.
- [DeepSeek App](https://download.deepseek.com/) - Mobile and desktop app downloads.

## Related

- [DeepSeek Discord](https://discord.gg/Tc7c45Zzu5) - Community channel linked from the API docs.
- [DeepSeek on X](https://x.com/deepseek_ai) - Release announcements.
- [Ollama Discord](https://discord.com/invite/ollama) - Help with local model issues.
- [Privacy Policy](https://cdn.deepseek.com/policies/en-US/deepseek-privacy-policy.html) - Worth reading before sending proprietary code through the API.
- [Terms of Use](https://cdn.deepseek.com/policies/en-US/deepseek-terms-of-use.html) - Same reason.

## Contributing

Open a pull request with a link that appears in DeepSeek's or Ollama's own pages and a one-line reason it belongs here.


_Last reviewed: 2026-09-22_
