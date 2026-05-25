<h1 align="center">
  <br>
  <img src="https://ararahq.com/logo-dark.png" alt="AraraHQ" width="200">
  <br>
  AraraHQ
  <br>
</h1>

<h3 align="center">Communication infrastructure for Latin America</h3>

<p align="center">
  <a href="https://ararahq.com">Website</a> &bull;
  <a href="https://docs.ararahq.com">Docs</a> &bull;
  <a href="https://docs.ararahq.com/quickstart">Quickstart</a> &bull;
  <a href="https://x.com/araaborern">Twitter</a>
</p>

---

### What is Arara?

Arara is the **developer-first WhatsApp API** for Latin America. Integrate in 5 minutes. Send templates, campaigns, and build conversational flows — all through a simple, clean API.

```typescript
import { NodeSDK } from '@ararahq/sdk';

const arara = new NodeSDK({ apiKey: 'ara_live_...' });

await arara.messages.send({
  receiver: 'whatsapp:+5511999999999',
  templateName: 'order_confirmation',
  variables: ['João', '#12345']
});
```

### Ecosystem

| Project | Description |
|---------|-------------|
| **[arara-node-sdk](https://github.com/ararahq/arara-node-sdk)** | Official Node.js / TypeScript SDK |
| **[arara-python-sdk](https://github.com/ararahq/arara-python-sdk)** | Official Python SDK (sync + async) |
| **[arara-java-sdk](https://github.com/ararahq/arara-java-sdk)** | Official Java SDK |
| **[arara-php-sdk](https://github.com/ararahq/arara-php-sdk)** | Official PHP SDK |
| **[arara-cli](https://github.com/ararahq/cli)** | Command-line interface (Go) |
| **[ararahq-mcp](https://github.com/ararahq/ararahq-mcp)** | MCP Server — plug Arara into Claude, Cursor, and AI agents |
| **[send-whatsapp-action](https://github.com/ararahq/send-whatsapp-action)** | GitHub Action for WhatsApp notifications |
| **[arara-vscode-theme](https://github.com/ararahq/arara-vscode-theme)** | VS Code color theme |
| **[docs](https://docs.ararahq.com)** | API documentation |

### Get Started

```bash
# Install the SDK
npm install @ararahq/sdk

# Or use the CLI
brew install ararahq/tap/arara
arara login
arara send --to +5511999999999 --template hello_world
```

### Built for Developers

- **5 minute integration** — validated by real customers, not marketing
- **4 SDKs** — Node.js, Python, Java, PHP
- **CLI with TUI** — interactive terminal dashboard
- **MCP Server** — AI agents send WhatsApp natively
- **Webhooks** — real-time delivery status and inbound messages
- **Sandbox mode** — test with `ara_test_` keys before going live

---

<p align="center">
  <sub>Built in Brazil, for Latin America.</sub>
</p>
