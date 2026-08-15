# Lab 2 — AI-Powered Data Analysis with LCEL

Part of [AI Agents with LangChain — Coursera Labs](../). From **Module 2: LCEL and Manual Tool Calling in LangChain** of IBM's [Fundamentals of Building AI Agents](https://www.coursera.org/learn/fundamentals-of-building-ai-agents) course.

## What this lab covers

- Building a small "DataWizard" agent: a set of LangChain tools that list available datasets, load and analyze CSV files, and generate summaries/statistics
- A caching layer that keeps a loaded dataset in memory so repeated questions don't reload the file each time
- Wiring the tools into an agent executor so a non-technical user can explore a dataset entirely through natural-language questions
- Graceful error handling for the kind of things that go wrong in an open-ended chat loop (bad column names, missing files, etc.)

## Tech stack

Python · LangChain · OpenAI · pandas · NumPy · scikit-learn

## Files

- [`ai_powered_data_analysis_lcel.ipynb`](./ai_powered_data_analysis_lcel.ipynb) — the completed notebook
