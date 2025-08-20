# Welcome to ATXP! 💰

**The payments layer for agents and MCP servers**

---

## About ATXP

ATXP is a framework for building and running agents that can interact with the world through a seamless payments layer. We enable agents to discover and call paid MCP tools while automatically handling payments from their own wallets.

### What We Do

- 💳 **Payment Infrastructure**: Built-in payments layer for agent-MCP interactions
- 🤖 **Agent Development**: Build agents that can pay for MCP tools automatically
- 🛠️ **MCP Monetization**: Add per-tool, per-call pricing to your MCP servers
- 🔐 **Secure Payments**: Signed payments authorize MCP server tool calls

---

## 🚀 Get Started

### 🤖 Build Agents That Pay for MCP Tools
Use the ATXP SDK client to connect your agent to MCP servers and automatically handle payments. Your agent brings a wallet (ATXP account or chain wallet), and each tool call is authorized and paid on demand.

**[🎮 Build & Run ATXP Agent Demo](https://github.com/atxp-dev/agent-demo)**

### 🛠️ Monetize Your MCP Server
Add the ATXP Express middleware and call `requirePayment` inside any tool handler to charge before execution. You set the price per tool; ATXP validates payment and then your tool runs.

### 📚 Documentation
**[📖 Visit ATXP Docs](https://docs.atxp.ai)**

Our documentation covers:
- Agent Quickstart guide
- MCP Server Quickstart guide
- SDK reference
- Payment integration examples
- Best practices for monetization

---

## 🛠️ Quick Start

### For Agent Developers
1. **Read the docs**: [ATXP Agent docs](https://docs.atxp.ai/client)
2. **Run the demo agent**: [agent-demo](https://github.com/atxp-dev/agent-demo)
3. **Agent quickstart**: [build your first agent](https://docs.atxp.ai/client/index)

### For MCP Server Developers
1. **Read the docs**: [ATXP MCP server docs](https://docs.atxpi.ai/server)
2. **Set Pricing**: Configure per-tool, per-call rates
3. **Require Payment**: Add `requirePayment` to tool handlers
4. **Deploy & Monetize**: Start earning from tool usage

---

## 🤝 Get Help

- 📖 **[Documentation](https://docs.atxp.ai)** - Agent and MCP server quickstart guides
- 💬 **[Community]https://discord.gg/StCPUPS2)** - Get support, show off what you're building, and chat with other builders

---

## 🌟 Why Choose ATXP?

- **Predictable Costs**: Pay-as-you-go for clients; per-use monetization for servers
- **Cross-Platform**: Works across major MCP hosts and your own deployments
- **Secure Payments**: Built-in payment validation and authorization

---

## 📈 Stay Updated

- ⭐ **Star our repos** to stay updated on releases
- 🔔 **Watch** for notifications on new features
- 📧 **Join** our [community of builders](https://discord.gg/StCPUPS2)

---

*Ready to monetize your MCP tools or build agents that pay? Start with [ATXP Docs](https://docs.atxp.ai) and [try our demo](https://github.com/atxp-dev/agent-demo)!*
