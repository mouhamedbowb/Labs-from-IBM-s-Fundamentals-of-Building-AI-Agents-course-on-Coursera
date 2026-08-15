# Lab 4 — Build a Tool Calling Agent

Part of [AI Agents with LangChain — Coursera Labs](../). From **Module 2: LCEL and Manual Tool Calling in LangChain** of IBM's [Fundamentals of Building AI Agents](https://www.coursera.org/learn/fundamentals-of-building-ai-agents) course.

## What this lab covers

- A YouTube-interaction toolset built from scratch: tools that extract a video ID from a URL, fetch its metadata, pull its transcript, and grab its thumbnails
- Chaining those tools together in a fixed sequence, then again as a recursive, multi-step chain
- Handing the collected data to an LLM with a structured prompt to generate a video summary
- The mechanics of manual tool calling versus letting an agent decide the sequence itself

## Tech stack

Python · LangChain · OpenAI · pytube · youtube-transcript-api · yt-dlp

## Files

- [`tool_calling_agent.ipynb`](./tool_calling_agent.ipynb) — the completed notebook

## Note

The 7-part exercise (repeating the pipeline on a new video) is still open — worked independently rather than copied from the course's official hints, in line with Coursera's Honor Code.
