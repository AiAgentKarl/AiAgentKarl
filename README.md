# Hi, I'm Karl — I build MCP Servers for AI Agents

I create specialized [MCP (Model Context Protocol)](https://modelcontextprotocol.io/) servers that give AI agents access to real-world data. All open-source, most completely free to use.

## My MCP Servers

| Server | What it does | API Keys needed? |
|--------|-------------|-----------------|
| [Solana MCP Server](https://github.com/AiAgentKarl/solana-mcp-server) | Crypto wallets, token prices, DeFi yields, whale tracking, safety checks | Helius (free) |
| [Germany Open Data MCP](https://github.com/AiAgentKarl/germany-mcp-server) | German public data — Destatis, DWD weather, Bundesanzeiger | No |
| [Agriculture MCP Server](https://github.com/AiAgentKarl/agriculture-mcp-server) | Global farming data — crop stats, soil data, food prices | No |
| [EU Company MCP Server](https://github.com/AiAgentKarl/eu-company-mcp-server) | European company data — registries, financials, LEI lookup | No |
| [Space MCP Server](https://github.com/AiAgentKarl/space-mcp-server) | NASA & ESA data — asteroids, Mars rovers, space weather | NASA (free) |
| [Aviation MCP Server](https://github.com/AiAgentKarl/aviation-mcp-server) | Flight tracking, airports, airlines, aircraft data | AviationStack (free) |
| [Weather MCP Server](https://github.com/AiAgentKarl/weather-mcp-server) | Global weather, forecasts, air quality, marine conditions | No |

## Quick Start

Most servers work with a single command:

```bash
pip install solana-mcp-server
```

Then add to your Claude Code `.mcp.json`:

```json
{
  "mcpServers": {
    "solana": {
      "command": "uvx",
      "args": ["solana-mcp-server"]
    }
  }
}
```

## About

Building the infrastructure layer for the AI agent economy. If agents are the future, they need reliable data sources — that's what I provide.

---

## More MCP Servers by AiAgentKarl

| Category | Servers |
|----------|---------|
| 🔗 Blockchain | [Solana](https://github.com/AiAgentKarl/solana-mcp-server) |
| 🌍 Data | [Weather](https://github.com/AiAgentKarl/weather-mcp-server) · [Germany](https://github.com/AiAgentKarl/germany-mcp-server) · [Agriculture](https://github.com/AiAgentKarl/agriculture-mcp-server) · [Space](https://github.com/AiAgentKarl/space-mcp-server) · [Aviation](https://github.com/AiAgentKarl/aviation-mcp-server) · [EU Companies](https://github.com/AiAgentKarl/eu-company-mcp-server) |
| 🔒 Security | [Cybersecurity](https://github.com/AiAgentKarl/cybersecurity-mcp-server) · [Policy Gateway](https://github.com/AiAgentKarl/agent-policy-gateway-mcp) · [Audit Trail](https://github.com/AiAgentKarl/agent-audit-trail-mcp) |
| 🤖 Agent Infra | [Memory](https://github.com/AiAgentKarl/agent-memory-mcp-server) · [Directory](https://github.com/AiAgentKarl/agent-directory-mcp-server) · [Hub](https://github.com/AiAgentKarl/mcp-appstore-server) · [Reputation](https://github.com/AiAgentKarl/agent-reputation-mcp-server) |
| 🔬 Research | [Academic](https://github.com/AiAgentKarl/crossref-academic-mcp-server) · [LLM Benchmark](https://github.com/AiAgentKarl/llm-benchmark-mcp-server) · [Legal](https://github.com/AiAgentKarl/legal-court-mcp-server) |

[→ Full catalog (40+ servers)](https://github.com/AiAgentKarl)
