Light Shell

A powerful AI interface in a tiny HTML file.

Light Shell is an ultra-lightweight AI chat interface built entirely in HTML, CSS and JavaScript.

The goal is simple: provide as many AI features as possible while keeping the entire application under 1 MB.

No installation. No complicated setup. No Light Shell account. Just one HTML file and your own API key.

---

✨ Why Light Shell?

Modern AI applications can be surprisingly large and resource-intensive.

Light Shell was created with a different philosophy:

Maximum functionality. Minimum size.

The current V4 version is approximately 90 KB while offering a surprisingly large set of features.

The project is designed to work on both smartphones and desktop computers, including low-end devices.

🚀 Features

AI Chat

- Streaming AI responses.
- Multiple conversations.
- Edit, delete, copy and regenerate messages.
- Custom API endpoints.
- Choose your own AI model.
- Adjustable temperature and response token limits.
- Configurable reasoning levels.

Memory & Context

- Persistent user memory.
- Optional automatic memory.
- Add and remove saved facts.
- Automatic conversation summarization.
- Manual summary editing.
- Pinned messages that remain in the model's context.
- Configurable context limits to reduce token usage.

Files & Code

- Attach text files and source code.
- Attach images for vision-capable models.
- Markdown rendering.
- Tables, lists, links and formatted text.
- Code blocks are converted into downloadable files instead of ordinary code blocks.
- Support for multiple programming languages.

AI Tools

- Optional internet search through OpenRouter Web Search.
- Optional isolated JavaScript sandbox.
- User permission required before enabling the sandbox.
- Adjustable sandbox access.
- The sandbox has no network, file, storage or API-key access.

API & Usage Management

- OpenRouter integration.
- Custom API URL.
- Custom model IDs.
- Connection testing.
- Model list retrieval.
- Optional API usage monitoring.
- Optional estimated balance protection for OpenRouter.

Data Management

- Local conversation history.
- Backup export.
- Backup import.
- API keys are excluded from exported backups.
- No mandatory cloud synchronization.

📱 Supported Devices

Light Shell is designed for modern browsers on:

- Android
- iOS
- Windows
- Linux
- macOS

No separate mobile or desktop application is required.

⚙️ How to Use

1. Download "рабочая_в4.html" from this repository.
2. Open "OpenRouter" (https://openrouter.ai/) and create an account.
3. Generate your API key.
4. Open the downloaded HTML file in your browser.
5. Open Settings.
6. Select OpenRouter or configure a compatible API endpoint.
7. Paste your API key.
8. Enter an available model ID.
9. Start chatting!

Important: You need an account with your chosen API provider. You do not need an account with Light Shell.

Some models are free, while others require credits. Model availability and pricing depend on the provider.

🔐 Privacy & Security

Light Shell does not require its own backend server.

In the current V4 version:

- Conversations, settings and memory are stored in the browser.
- API keys are stored in the browser's local storage.
- API requests are sent directly to the configured provider.
- API keys are not included in exported backups.

Your prompts and attached files are transmitted to the selected AI provider when you make requests.

Security note: Do not use your API key on shared or untrusted devices. Browser storage is not an encrypted secret vault.

Optional internet search may send search queries and relevant context to the search provider. Additional charges may apply.

⚠️ Limitations

- API compatibility depends on the selected provider.
- Some providers block direct browser requests through CORS.
- Internet search requires a supported OpenRouter configuration.
- The sandbox supports JavaScript only, not Python or a full operating-system environment.
- Browser storage limits depend on the browser and available device storage.
- Image generation and video generation are not yet included in the current V4 version.

🛠️ Project Philosophy

Light Shell is intentionally developed as a single HTML file.

The project does not aim to become a large application with complicated installation procedures.

Its main principles are:

1. Keep the application lightweight.
2. Preserve the single-file architecture.
3. Support low-end devices.
4. Give users freedom to choose their AI providers and models.
5. Avoid mandatory registration and infrastructure.
6. Add useful functionality without exceeding the 1 MB project limit.

📖 The Story Behind the Project

One day, I was running out of storage space on my device and decided to clean it up.

Eventually, I deleted my AI application.

But then I started wondering:

Why do AI applications need so much storage space?

That simple question became the starting point of Light Shell.

What began as a small experiment eventually turned into a much more ambitious project.

The project is built with the help of AI tools, free AI credits, spare time and, most importantly, enthusiasm.

👨‍💻 Developer

Created by: tet0r

This project is independently developed.

AI-assisted development has played an important role in building and improving Light Shell.

---

Light Shell — Maximum AI functionality. Minimum application size.
