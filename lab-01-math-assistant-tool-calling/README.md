# Lab 1 — Math Assistant with Tool Calling

Part of [AI Agents with LangChain — Coursera Labs](../). From **Module 1: Foundations of Tool Calling and Chaining** of IBM's [Fundamentals of Building AI Agents](https://www.coursera.org/learn/fundamentals-of-building-ai-agents) course.

## What this lab covers

- Two ways to turn a Python function into a LangChain tool: the `Tool` class and the `@tool` decorator, and why the decorator is the more modern approach for structured inputs/outputs
- How an agent decides which tool to call, based on the LLM's step-by-step reasoning (reason → act → observe)
- Orchestrating four tools — add / subtract / multiply / divide — behind a single agent
- Debugging a real tool-logic bug: a subtraction tool that silently negated its first input, so "100, 20, 10" returned -130 instead of 70 — traced back to a mismatch between the tool's math and the agent's assumptions
- Extending the agent with a built-in Wikipedia tool, so it can mix factual lookups with calculations in one query
- Comparing the legacy `initialize_agent` (`AgentExecutor`) with the newer, graph-based `create_react_agent` from LangGraph

## Tech stack

Python · LangChain · LangGraph · IBM watsonx.ai (Granite) · OpenAI

## Files

- [`ai_math_assistant_langchain.ipynb`](./ai_math_assistant_langchain.ipynb) — the completed notebook

## Note

The exercise section (custom power tool) was completed independently rather than copied from the course's official solution key, in line with Coursera's Honor Code.
