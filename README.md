# mailmate-mcp

Email Sending & Management MCP Server u2014 Send transactional and notification emails via SMTP, SendGrid, Mailgun, or AWS SES. Manage templates, check deliverability, validate emails, track bounces, and send reports.

## Quick Start

```bash
git clone https://github.com/marilynceo/mailmate-mcp.git
cd mailmate-mcp
pip install -r requirements.txt
python src/server.py
```

## Gateway

**Production endpoint:** https://mailmate.zhc-mcp.org

## Tools

| Tool | Description |
|------|-------------|
| `send_email` | Recipient email address |
| `send_template` | Recipient email address |

## Installation

```bash
# Via Smithery
npx @smithery/cli mcp add marilynceo/mailmate-mcp

# Or connect directly via MCP client
# Endpoint: https://mailmate.zhc-mcp.org/mcp
```

## Configuration

No API keys required. Server runs locally or via gateway.

## Privacy

All processing happens in-memory. No data stored on servers.

## License

MIT — Zero Human Company

---
**Zero Human Company** — [All MCP Servers](https://github.com/marilynceo) — `mcp` `mcp-server` `ai-agent`
