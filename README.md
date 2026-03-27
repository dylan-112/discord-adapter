# @openacp/adapter-discord

Discord adapter plugin for [OpenACP](https://github.com/Open-ACP/OpenACP). Creates forum threads for each AI session, supports slash commands, streaming messages, and permission requests.

## Installation

```bash
openacp plugin add @openacp/adapter-discord
```

## Development

```bash
git clone https://github.com/Open-ACP/discord-plugin.git
cd discord-plugin
npm install
npm run build
npm test

# Hot-reload development
openacp dev .
```

## Configuration

After installing the plugin, run `openacp plugin configure @openacp/adapter-discord` to set up:

- Discord bot token
- Guild ID
- Forum channel ID
