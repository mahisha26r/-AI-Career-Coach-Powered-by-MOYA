#  AI Career Coach – Powered by MOYA


## Features

- **Agent Management**: Create, register, and manage multiple AI agents.
- **Orchestration**: Orchestrate conversations and tasks across multiple agents.
- **Memory Tools**: Integrate memory tools to maintain conversation context and history.
- **Streaming Responses**: Support for streaming responses from agents.
- **Extensibility**: Easily extend the framework with new agents, tools, and orchestrators.

## Getting Started

```bash
pip install moya-ai  # Only core framework
pip install moya-ai[all] # All the supported services such as OpenAI, Bedrock, Ollama, Crewai
# or install specific ones - for example openai and ollama
pip install moya-ai[openai, ollama]
```


# Contributing to MOYA

We accept contributions exclusively through forked repositories. Please follow these steps:

1. Fork this repository to your GitHub account
2. Create a new branch in your fork for your changes
3. Make your changes and commit them to your branch
4. Submit a pull request from your fork's branch to our main repository

### Prerequisites

- Python 3.10+
- Install required dependencies:
  ```bash
  pip install .
  ```

### Quick Start Examples

#### OpenAI Agent

Interactive chat example using OpenAI agent with conversation memory.

```python
# filepath: ~/github/moya/examples/quick_start_openai.py

python -m examples.quick_start_openai

```
