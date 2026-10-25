# ORCHAI and your privacy

ORCHAI runs on your computer. It sends nothing about you or your use to its developers:
no telemetry, no analytics, no crash reports sent on their own.

What leaves your computer, and only because you set it up:

- **The model services you add.** A request to a cloud model (Anthropic, OpenAI, Google
  Gemini or another service) carries what that request needs — your message, and the files
  or results the task uses — to that service, under its own terms. A model on your computer
  (Ollama, LM Studio) keeps everything local.
- **The connections and integrations you add** (Telegram, MCP servers, web pages a task
  fetches), each only for what a task asks of it, with your approval where ORCHAI asks for one.
- **Checking for updates**, when that is available: the app asks the public ORCHAI releases
  page whether a newer version exists. Nothing about you is sent.

What stays on your computer: your works, conversations, files, knowledge, settings and the
service's log, in ORCHAI's data folder. API keys stay in your system's keychain.

A diagnostics file is made only when you ask for one (Settings → Diagnostics); it holds no
API key and nothing you wrote, and you decide whom to send it to.
