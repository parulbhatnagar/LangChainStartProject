# LangChain Start Project

Goal of this project is to learn basics of LangChain and build few agentic flows.

This repository contains different notebooks with step-by-step implementations following the [LangChain Documentation](https://docs.langchain.com/oss/python/langchain/overview).

## Notebooks Overview

| Notebook | Description | Key Concepts |
|----------|-------------|--------------|
| `basicAgent.ipynb` | Introduction to creating a simple agent that can answer questions and call tools. Demonstrates basic agent setup with a weather tool. | `create_agent`, Tools, Basic LLM Integration, Function Calling |
| `weatherAgentWithTools.ipynb` | A practical weather forecasting agent demonstrating production-ready concepts including detailed system prompts, tool integration, structured output, conversational memory, and runtime context injection. | System Prompts, Tool Runtime Context, Structured Output, InMemorySaver, Conversational Memory, Context Schema |

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone <repo-url>
   cd LangChainStartProject
   ```

2. **Set up environment variables:**
   Create a `.env` file with your OpenAI API key:
   ```
   OPENAI_API_KEY=your_api_key_here
   ```

3. **Install dependencies:**
   ```bash
   uv add langchain python-dotenv ipykernel
   ```

4. **Run notebooks:**
   Open any `.ipynb` file in VS Code or Jupyter and execute the cells.

## Project Structure

- `basicAgent.ipynb` - Simple agent implementation
- `weatherAgentWithTools.ipynb` - Advanced agent with tools and memory
- `.env` - Environment variables (not committed to git)
- `README.md` - This file

## References

- [LangChain Documentation](https://docs.langchain.com/oss/python/langchain/overview)
- [LangChain GitHub](https://github.com/langchain-ai/langchain)