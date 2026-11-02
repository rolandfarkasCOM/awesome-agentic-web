# Awesome Agentic Web [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Protocols, tools, and specifications for the agentic web - how AI agents discover, understand, and act on websites.

The web was built for human eyes. As AI agents start to browse, buy, and act on people's behalf, a new layer of open standards and tooling is emerging so sites can describe themselves to agents, and agents can transact safely. This is a curated list of that ecosystem.

All entries are open source.

## Contents

- [Protocols & standards](#protocols--standards)
- [Discovery & site manifests](#discovery--site-manifests)
- [Payments & commerce](#payments--commerce)
- [MCP SDKs & servers](#mcp-sdks--servers)
- [Agent frameworks & orchestration](#agent-frameworks--orchestration)
- [Web & browser agents](#web--browser-agents)
- [Related lists](#related-lists)

## Protocols & standards

- [Model Context Protocol](https://github.com/modelcontextprotocol/modelcontextprotocol) - Anthropic's open standard for connecting AI models to tools and data sources.
- [Agent2Agent (A2A)](https://github.com/a2aproject/A2A) - Open protocol for interoperability between independent AI agents, now under the Linux Foundation.
- [Agent Protocol](https://github.com/agi-inc/agent-protocol) - Framework-agnostic common interface for interacting with AI agents.

## Discovery & site manifests

- [llms.txt](https://github.com/AnswerDotAI/llms-txt) - Proposed `/llms.txt` standard that gives language models a curated, markdown-friendly map of a website.
- [NLWeb](https://github.com/nlweb-ai/NLWeb) - Reference implementation for turning websites into conversational, agent-queryable endpoints.
- [WebMCP](https://github.com/webmachinelearning/webmcp) - W3C Community Group proposal for a browser API that lets web pages expose tools to agents.
- [AI2Web](https://github.com/ai2web-foundation/ai2web-spec) - Specification for describing a site's capabilities once and projecting them to MCP, ACP, AP2, and REST.

## Payments & commerce

- [Agentic Commerce Protocol (ACP)](https://github.com/agentic-commerce-protocol/agentic-commerce-protocol) - Open standard for agent-initiated checkout maintained by OpenAI and Stripe, behind ChatGPT Instant Checkout.
- [Agent Payments Protocol (AP2)](https://github.com/google-agentic-commerce/AP2) - Google-led open protocol for secure, mandate-based payments between agents and merchants.
- [x402](https://github.com/coinbase/x402) - Coinbase's HTTP-native payments protocol reviving the 402 "Payment Required" status for machine payments.
- [a2a-x402](https://github.com/google-agentic-commerce/a2a-x402) - Extension bringing x402 payments to the A2A protocol so agents can pay for services.
- [Stripe Agent Toolkit](https://github.com/stripe/ai) - Stripe's toolkit for adding payments and financial tools to AI agents.

## MCP SDKs & servers

- [MCP Python SDK](https://github.com/modelcontextprotocol/python-sdk) - Official Python SDK for building MCP servers and clients.
- [MCP TypeScript SDK](https://github.com/modelcontextprotocol/typescript-sdk) - Official TypeScript SDK for building MCP servers and clients.
- [MCP C# SDK](https://github.com/modelcontextprotocol/csharp-sdk) - Official C# SDK for MCP, maintained with Microsoft.
- [MCP Go SDK](https://github.com/modelcontextprotocol/go-sdk) - Official Go SDK for MCP, maintained with Google.
- [MCP Java SDK](https://github.com/modelcontextprotocol/java-sdk) - Official Java SDK for MCP, maintained with Spring AI.
- [MCP Servers](https://github.com/modelcontextprotocol/servers) - Official reference collection of MCP server implementations.
- [FastMCP](https://github.com/jlowin/fastmcp) - Fast, Pythonic framework for building MCP servers and clients.

## Agent frameworks & orchestration

- [OpenAI Agents SDK](https://github.com/openai/openai-agents-python) - OpenAI's lightweight framework for building multi-agent workflows.
- [Google ADK](https://github.com/google/adk-python) - Google's open, code-first toolkit for building, evaluating, and deploying agents.
- [LangGraph](https://github.com/langchain-ai/langgraph) - LangChain's library for building stateful, resilient multi-agent applications as graphs.
- [CrewAI](https://github.com/crewAIInc/crewAI) - Framework for orchestrating role-playing, autonomous, collaborating AI agents.
- [AutoGen](https://github.com/microsoft/autogen) - Microsoft's programming framework for agentic AI and multi-agent conversations.
- [PydanticAI](https://github.com/pydantic/pydantic-ai) - Agent framework from the Pydantic team for building production apps with LLMs.
- [Agno](https://github.com/agno-agi/agno) - Full-stack framework for building, running, and managing multi-agent systems.

## Web & browser agents

- [browser-use](https://github.com/browser-use/browser-use) - Makes websites accessible to AI agents by automating browser tasks.
- [Stagehand](https://github.com/browserbase/stagehand) - SDK for building browser agents that combine code and natural-language actions.
- [Skyvern](https://github.com/Skyvern-AI/skyvern) - Automates browser-based workflows using LLMs and computer vision.
- [Nanobrowser](https://github.com/nanobrowser/nanobrowser) - Open-source Chrome extension for multi-agent web automation using your own LLM key.
- [LaVague](https://github.com/lavague-ai/LaVague) - Large Action Model framework for developing AI web agents.
- [ClawBench](https://github.com/reacher-z/ClawBench) - Open benchmark for evaluating browser agents on real-world tasks across live websites with request-level outcome checks and execution traces.

## Related lists

- [Awesome MCP Servers](https://github.com/punkpeye/awesome-mcp-servers) - Large curated collection of Model Context Protocol servers.
- [Awesome A2A](https://github.com/ai-boost/awesome-a2a) - Curated resources, tools, servers, and clients for the A2A protocol.
- [Awesome AI Agents](https://github.com/ianwieds/awesome-ai-agents) - Curated list of agent frameworks, browser and computer-use agents, tools, protocols and research.

## Contributing

Contributions are welcome! Please read the [contribution guidelines](contributing.md) first. Every entry must be open source, actively maintained, and directly relevant to the agentic web.
