# ANVISA: Processo

### ANVISA: Processo for Claude, ChatGPT and AI agents

ANVISA: Court Case, official-source lookup. Platform-hosted, pay per query with prepaid credit.

- 📊 **1 tool**
- 🔒 **Read-only**
- 💬 **Works with any MCP client**: Claude Desktop, Cursor, VS Code, Cline, Continue
- 🔑 **Magic-link login (no password)**

[Portuguese version](README.md) · [Full docs (PT-BR)](docs/)

---

## One-click install

### Claude (Web and Desktop)

[➕ Open in Claude and connect](https://claude.ai/new?modal=add-custom-connector#settings/customize-connectors)

Manual: [claude.ai/customize/connectors](https://claude.ai/customize/connectors?surface=cowork) → **+** → **Add custom connector** → name `ANVISA: Processo`, URL `https://api.mcp.ai/p_anvisa_processo`.

### Cursor

[➕ Install in Cursor](cursor://anysphere.cursor-deeplink/mcp/install?name=anvisa_processo&config=eyJ1cmwiOiJodHRwczovL2FwaS5tY3AuYWkvcF9hbnZpc2FfcHJvY2Vzc28ifQ==)

### VS Code (Copilot Chat)

[➕ Install in VS Code](vscode:mcp/install?name=anvisa_processo&config=%7B%22type%22%3A%22http%22%2C%22url%22%3A%22https%3A%2F%2Fapi.mcp.ai%2Fp_anvisa_processo%22%7D)

### Any other MCP-over-HTTP client

```
https://api.mcp.ai/p_anvisa_processo
```

---

## 1 tool

| Tool | Description |
|---|---|
| `anvisa_processo_consultar` | ANVISA: Processo, consulta em fonte oficial. |

---

## Pricing

See [docs/precos.md](docs/precos.md) (PT-BR).

---

## License

MIT — see [LICENSE](LICENSE). The MCP server at `api.mcp.ai/p_anvisa_processo` is proprietary (hosted); this repo (manifests, docs, skills) is MIT.
