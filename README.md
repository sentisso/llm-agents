# LangX AI agents
This repository contains some rather simple LLM agents that I implemented in order to learn the [LangChain](https://python.langchain.com/docs/introduction/) and [LangGraph](https://langchain-ai.github.io/langgraph/) frameworks:
- `apps/calculator.ipynb`
  - LangGraph agent capable of calculating simple math calculations
  - makes use of `+`/`-`/`/`/`*` math operations as tools
  - capable of recovery from erroneous tool use
  - has persistent short-term memory stored in a Postgres database

_(by LangX I mean both LangChain/LangGraph)_