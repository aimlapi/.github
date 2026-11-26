# AI/ML API

One OpenAI-compatible API for 10,000+ AI models and tools: chat, reasoning, image, video, music, speech, embeddings and OCR. One key, one balance, and the SDKs you already use.

```bash
curl https://api.aimlapi.com/v1/chat/completions \
  -H "Authorization: Bearer $AIMLAPI_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{"model": "openai/gpt-5-mini", "messages": [{"role": "user", "content": "Hello"}]}'
```

Get a key at [aimlapi.com/app/keys](https://aimlapi.com/app/keys). Docs: [docs.aimlapi.com](https://docs.aimlapi.com).

## Run your coding agent on any model

```bash
npx aimlapi claude
```

The `aimlapi` CLI signs you in through the browser, creates a key and starts your agent connected to AI/ML API. It works with Claude Code, Codex, OpenCode, Cline, OpenClaude, OpenClaw, Hermes Agent, zero and ZCode.

Claude Code can run on DeepSeek, GLM, Qwen or Gemini, and Codex on Claude or Kimi. The API serves the Anthropic Messages and OpenAI Responses formats for every chat model that calls tools, so the Anthropic and OpenAI SDKs work with them too.

[CLI docs](https://docs.aimlapi.com/quickstart/cli) · [Messages and Responses on any model](https://docs.aimlapi.com/capabilities/messages-and-responses)

## Teach your agent to build on AI/ML API

[skills](https://github.com/aimlapi/skills) holds 13 Agent Skills for Claude Code, Cursor, Codex, OpenCode, Gemini CLI, Windsurf and other agents. With them, an agent takes models, parameters and prices from the live catalogue, waits on long jobs the way the API expects, and tests in sandbox mode before it spends anything.

```bash
curl -fsSL https://aimlapi.com/skills/install.sh | sh
```

Or `npx @ai-ml.api/skills install`, or `/plugin marketplace add aimlapi/skills` in Claude Code. The `aimlapi` CLI installs them with your agent.

## Repositories

| Repository | What it is |
| --- | --- |
| [skills](https://github.com/aimlapi/skills) | Agent Skills for coding agents |
| [mcp](https://github.com/aimlapi/mcp) | Remote MCP server: search, compare and call models from Claude Code, Gemini CLI, Qwen Code, Qoder or Cline. OAuth sign-in, no key to paste |
| [aimlapi-sdk-python](https://github.com/aimlapi/aimlapi-sdk-python) | Python SDK, based on the OpenAI SDK |
| [aimlapi-sdk-node](https://github.com/aimlapi/aimlapi-sdk-node) | TypeScript and JavaScript SDK |
| [langchain-aimlapi](https://github.com/aimlapi/langchain-aimlapi) | LangChain integration |
| [dify-aimlapi-plugin](https://github.com/aimlapi/dify-aimlapi-plugin) | Model provider plugin for Dify |
| [hermes-provider-aimlapi](https://github.com/aimlapi/hermes-provider-aimlapi) | Model provider plugin for Hermes Agent |
| [api-docs](https://github.com/aimlapi/api-docs) | Source of [docs.aimlapi.com](https://docs.aimlapi.com) |

The other repositories ending in `-aimlapi` are forks of open-source apps that we connect to AI/ML API.

For agents reading docs: [llms.txt](https://docs.aimlapi.com/llms.txt). Append `.md` to any docs URL to get Markdown.

[Website](https://aimlapi.com/gh) · [X](https://x.com/aimlapi) · help@aimlapi.com
