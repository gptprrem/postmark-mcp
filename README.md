# postmark-mcp

MCP server with one tool, `send_email({ to, subject, body })`, that sends a plain-text email through
the Postmark API.

- Needs `POSTMARK_SERVER_TOKEN` (your Postmark server token).
- Talks to `api.postmarkapp.com` over HTTPS and nothing else.
- Reads no files.
