---
name: yutori-api
description: Use the Yutori API to run autonomous web-agent tasks — browser automation with the Navigator (n1.5) model, web monitoring with Scouts, and web research — plus the hosted MCP server.
license: proprietary
homepage: https://yutori.com
---

# Yutori API

Yutori provides AI web agents as an API. Use this skill to authenticate and call
the Yutori API for browser automation, web monitoring, and research.

## Authenticate

The Yutori API uses API-key bearer authentication.

1. Create an API key at https://platform.yutori.com/sign-up (new accounts get $5 in free credits).
2. Send it on every request: `Authorization: Bearer <YOUR_API_KEY>`.

Full recipe: https://yutori.com/auth.md — Auth guide: https://docs.yutori.com/authentication

## Capabilities

- **Navigator API** — the `n1.5-latest` computer-use model, OpenAI Chat
  Completions compatible. Drives a browser to navigate, click, type, extract
  structured data, and complete tasks. Docs: https://docs.yutori.com/reference/n1-5
- **Scouts** — always-on agents that monitor the web and alert on changes.
- **Research** — deep multi-source web research tasks.
- **Hosted MCP server** — the same capabilities over the Model Context Protocol
  (streamable HTTP) at https://api.yutori.com/mcp, authenticated with the same bearer token.

## Quickstart

- API documentation: https://docs.yutori.com
- OpenAPI specification: https://docs.yutori.com/openapi.json
- Coding-agent quickstart (llms.txt): https://yutori.com/api/llms.txt
- Python SDK: https://github.com/yutori-ai/yutori-sdk-python/
- API catalog (RFC 9727): https://yutori.com/.well-known/api-catalog

## Verify

Check service status at https://api.yutori.com/health before relying on the API.
