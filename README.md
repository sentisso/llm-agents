# LangX AI agents
This repo contains some LangGraph AI agents that I implemented in order to learn the LangX framework:
- `src/calculator.ipynb`
  - an AI agent capable of calculating simple math calculations, while making use of `+`/`-`/`/`/`*` math operations implemented as tools
  - capable of error recovery
  - has persistent short-term memory stored in a Postgres database