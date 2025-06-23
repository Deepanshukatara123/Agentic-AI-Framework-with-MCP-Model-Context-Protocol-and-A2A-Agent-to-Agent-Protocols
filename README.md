# Agentic-AI-Framework-with-MCP-Model-Context-Protocol-and-A2A-Agent-to-Agent-Protocols

Build scalable multi-agent workflows using Azure AI Agent Service, AutoGen based on Microsoft’s Educator Developer post .

This repository demonstrates how to orchestrate three specialized agents to automate a blog content pipeline:

Content Collection Agent: Gathers background info using Bing grounding.

Writer Agent: Drafts blog posts using LLMs like Llama 3 or Mistral.

Save Agent: Persists the final content via Azure AI Agent Service's code-interpreter.

You can orchestrate them using either:

AutoGen (Python)

Semantic Kernel (Python / C#)

This enables collaboration across agents to accomplish complex end-to-end tasks .
