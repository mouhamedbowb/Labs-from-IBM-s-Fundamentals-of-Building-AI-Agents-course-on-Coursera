# Lab 3 — Build Interactive LLM Agents with Tools

Part of [AI Agents with LangChain — Coursera Labs](../). From **Module 2: LCEL and Manual Tool Calling in LangChain** of IBM's [Fundamentals of Building AI Agents](https://www.coursera.org/learn/fundamentals-of-building-ai-agents) course.

## What this lab covers

- Binding custom tools directly to a chat model instead of going through a prebuilt agent
- Extracting the tool name and arguments the LLM decides to call from its response
- Invoking the right tool with those arguments and feeding the result back into the conversation
- Wrapping that whole request → tool call → response loop into a reusable agent class

## Tech stack

Python · LangChain · OpenAI

## Files

- [`interactive_tool_calling_agent.ipynb`](./interactive_tool_calling_agent.ipynb) — the completed notebook

## Note

The three exercises (a `calculate_tip` tool, manual tool-calling with an LLM, and a tip-calculating agent class) are still open — worked independently rather than copied from the course's official solution key, in line with Coursera's Honor Code.
