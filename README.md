# AI Agents with LangChain — Coursera Labs

Hands-on projects from IBM's [Fundamentals of Building AI Agents](https://www.coursera.org/learn/fundamentals-of-building-ai-agents) course on Coursera (part of the RAG and Agentic AI Professional Certificate). This repo tracks what I build as I work through the course — each lab lives in its own folder with its own README.

## About the course

- **Provider:** IBM, via Coursera
- **Focus:** designing AI agents that reason, call tools, and complete multi-step tasks — tool calling & chaining with LangChain, LangChain Expression Language (LCEL), manual tool calling, and built-in LangChain agents for data analysis and SQL

## Labs

| # | Lab | Module | What it covers |
|---|-----|--------|-----------------|
| 1 | [Math Assistant with Tool Calling](./lab-01-math-assistant-tool-calling) | 1 · Foundations of Tool Calling & Chaining | Custom tools, orchestrating a 4-tool math agent, debugging a tool-logic bug |
| 2 | [AI-Powered Data Analysis with LCEL](./lab-02-ai-powered-data-analysis-lcel) | 2 · LCEL & Manual Tool Calling | Natural-language querying of a CSV dataset via a caching data-science toolset |
| 3 | [Interactive LLM Agents with Tools](./lab-03-interactive-tool-calling-agent) | 2 · LCEL & Manual Tool Calling | Manual tool binding & extraction, wrapped into a reusable agent class |
| 4 | [Tool Calling Agent](./lab-04-tool-calling-agent) | 2 · LCEL & Manual Tool Calling | Chained tools that fetch and summarize a YouTube video (transcript, metadata, thumbnails) |
| 5 | [Data Visualization Agent](./lab-05-data-visualization-agent) | 3 · Using Built-in Agents | Natural-language charts and graphs over a CSV via `create_pandas_dataframe_agent` |
| 6 | Natural Language SQL Agent | 3 · Using Built-in Agents | Converts natural language into MySQL queries over a sample database — *in progress* |

See each lab's own README for full details.

## Tech stack

Python · LangChain / LangGraph · IBM watsonx.ai (Granite) · OpenAI · pandas & scikit-learn · Matplotlib / Seaborn · YouTube data APIs

## Attribution

This repository documents my own work completing IBM's course labs. Course content, lab instructions, and starter materials belong to IBM / Coursera — see the [course page](https://www.coursera.org/learn/fundamentals-of-building-ai-agents) for the original.
