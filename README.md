# Zen swarm

![Screenshot_3](https://github.com/user-attachments/assets/a1833b6e-f550-4f5a-b1ee-c394d68b522d)

🍃 Features

    🛠️ Full-featured, Twitter connectors
    🔗 Support for every model (Llama, Grok, OpenAI, Anthropic, etc.)
    👥 Multi-agent and room support
    📚 Easily ingest and interact with your documents
    💾 Retrievable memory and document store
    🚀 Highly extensible - create your own actions and clients
    ☁️ Supports many models (local Llama, OpenAI, Anthropic, Groq, etc.)
    📦 Just works!

AI Agent Dev School
🎯 Use Cases

    🤖 Chatbots
    🕵️ Autonomous Agents
    📈 Business Process Handling
    🎮 Video Game NPCs
    🧠 Trading

🚀 Quick Start
Prerequisites

    Python 2.7+
    Node.js 23+
    pnpm

    Note for Windows Users: WSL 2 is required.

Use the Starter (Recommended)

git clone https://github.com/zenswarm/zen-starter.git

cp .env.example .env

pnpm i && pnpm build && pnpm start

Then read the Documentation to learn how to customize your Swarm.
Manually Start Swarm (Only recommended if you know what you are doing)

# Clone the repository
git clone https://github.com/zenswarm/zen.git

# Checkout the latest release
# This project iterates fast, so we recommend checking out the latest release
git checkout $(git describe --tags --abbrev=0)
