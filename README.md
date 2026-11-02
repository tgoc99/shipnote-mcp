# ShipNote

[ShipNote](https://www.shipnote.co) prints, stamps and mails real postcards: one thank-you card to your aunt, or a card for everyone on your list. This plugin connects Cursor to ShipNote's hosted MCP server. It holds configuration only; the server runs at shipnote.co.

## What it does

| Tool | What it does |
|---|---|
| `list_card_designs` | Lists occasions and card designs. Read-only. |
| `quote_price` | Prices a number of postcards mailed within the US. Read-only. |
| `create_draft` | Saves your cards as a draft and returns a link. |

Nothing is mailed or charged from chat. You open the link, add your return address, check every card and pay on shipnote.co. Cards mail to US addresses only.

## Setup

Install the plugin. No account, API key or sign-in is needed.

To add it by hand, use this in your MCP configuration:

```json
{
  "mcpServers": {
    "shipnote": {
      "url": "https://www.shipnote.co/api/mcp/claude"
    }
  }
}
```

## Try it

- "Show me wedding thank-you card designs."
- "How much for 42 postcards?"
- "Here's our baby shower registry, can you make thank-you postcards?" (then paste it)

## Links

- [How it works with AI assistants](https://www.shipnote.co/ai-assistants)
- [Privacy policy](https://www.shipnote.co/privacy)
- Support: hello@shipnote.co
