# 📝 contractOracle

**DORA Execution MCP Server** — 10 tools | Part of [ToolOracle](https://tooloracle.io)

![Tools](https://img.shields.io/badge/MCP_Tools-10-10B898?style=flat-square)
![Status](https://img.shields.io/badge/Status-Live-00C853?style=flat-square)
![Tier](https://img.shields.io/badge/Tier-Enterprise-FF6D00?style=flat-square)
![Bus](https://img.shields.io/badge/Oracle_Bus-Connected-00C853?style=flat-square)

## Quick Connect

```bash
# Claude Desktop / Cursor / Windsurf
npx -y mcp-remote https://tooloracle.io/contract/mcp/
```

```json
// claude_desktop_config.json
{
  "mcpServers": {
    "contractoracle": {
      "command": "npx",
      "args": ["-y", "mcp-remote", "https://tooloracle.io/contract/mcp/"]
    }
  }
}
```

## Tools (10)

| Tool | Description |
|------|-------------|
| `register_contract` | Add or update an ICT third-party contract. Tracks all DORA Art. 30 mandatory cla |
| `list_contracts` | List contracts with optional filters. |
| `clause_check` | Validate a contract against all DORA Art. 30 mandatory clauses (standard + CIF). |
| `subcontracting_chain` | Map and assess the subcontracting chain of a contract (RTS on subcontracting). |
| `exit_readiness` | Evaluate exit plan readiness for a contract — Art. 28(8) exit strategies. |
| `cif_analysis` | Analyze all Critical/Important Function contracts for enhanced Art. 30(3) requir |
| `contract_gaps` | Identify missing mandatory clauses across all contracts. |
| `contract_scoring` | Red-flag risk scoring: exit risk, lock-in, jurisdiction, subcontracting gaps. |
| `contract_expiry` | Upcoming contract expirations and renewal deadlines. |
| `health_check` | Server status. |

## Pricing

| Tier | Rate Limit | Price |
|------|-----------|-------|
| Free | 10 calls/day | €0 |
| Pro | 1,000 calls/day | €99/month |
| Enterprise | Unlimited | Custom |

> **Note:** This is a compliance oracle. Full tool access requires a Pro or Enterprise subscription. Free tier includes read-only assessment tools.

## Part of ToolOracle

contractOracle is one of **42 specialized MCP servers** in the [ToolOracle](https://tooloracle.io) ecosystem — the largest collection of production-ready MCP tools for AI agents.

### DORA Coverage

**Related Oracles:**
- [FeedOracle](https://feedoracle.io) — Evidence-grade compliance data infrastructure
- [ToolOracle](https://tooloracle.io) — 42 Oracles, 390+ MCP Tools

## Links

- 🌐 Live: `https://tooloracle.io/contract/mcp/`
- 📚 Docs: [tooloracle.io/docs](https://tooloracle.io/docs)
- 🏠 Platform: [tooloracle.io](https://tooloracle.io)

---

*Built by [FeedOracle](https://feedoracle.io) — Evidence by Design*
