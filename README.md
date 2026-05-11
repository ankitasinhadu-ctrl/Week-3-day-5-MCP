# MCP + LangChain Integration Lab

## Overview

This lab demonstrates how to integrate MCP (Model Context Protocol) with LangChain agents.

The project shows how AI agents can connect to external systems like files, APIs, and databases using MCP tools and resources.

In this lab, we use a filesystem MCP server so the agent can:

- List files
- Read documents
- Search content
- Summarize files
- Create new files

We also compare MCP integration with direct API integration to understand their differences, advantages, and trade-offs.

---

# Learning Objectives

By completing this lab, you will learn how to:

- Connect LangChain agents to MCP servers
- Load MCP tools into LangChain
- Use MCP resources as agent context
- Build an MCP-enabled AI agent
- Compare MCP vs direct API integration

---

# Technologies Used

- Python
- LangChain
- OpenAI
- MCP (Model Context Protocol)
- langchain-mcp-adapters
- Filesystem MCP Server

---


├── lab_summary.md
├── requirements.txt
├── README.md
└── .env
