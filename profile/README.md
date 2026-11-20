# AI/ML API

One OpenAI-compatible API for 10,000+ AI models and tools: chat, reasoning, image, video, music, speech, embeddings and OCR. One key, one balance, and the SDKs you already use.

```bash
curl https://api.aimlapi.com/v1/chat/completions \
  -H "Authorization: Bearer $AIMLAPI_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{"model": "openai/gpt-5-mini", "messages": [{"role": "user", "content": "Hello"}]}'
```

Get a key at [aimlapi.com/app/keys](https://aimlapi.com/app/keys). Docs: [docs.aimlapi.com](https://docs.aimlapi.com).

## Connect your coding agent

| Repository | What it is |
| --- | --- |
| [mcp](https://github.com/aimlapi/mcp) | Remote MCP server: search, compare and call models from Claude Code, Gemini CLI, Qwen Code, Qoder or Cline. OAuth sign-in, no key to paste |
| [aimlapi-sdk-python](https://github.com/aimlapi/aimlapi-sdk-python) | Python SDK, based on the OpenAI SDK |
| [aimlapi-sdk-node](https://github.com/aimlapi/aimlapi-sdk-node) | TypeScript and JavaScript SDK |
| [langchain-aimlapi](https://github.com/aimlapi/langchain-aimlapi) | LangChain integration |
| [dify-aimlapi-plugin](https://github.com/aimlapi/dify-aimlapi-plugin) | Model provider plugin for Dify |

For agents reading docs: [llms.txt](https://docs.aimlapi.com/llms.txt). Append `.md` to any docs URL to get Markdown.

[Website](https://aimlapi.com) · [X](https://x.com/aimlapi) · help@aimlapi.com
