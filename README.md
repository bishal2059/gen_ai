# Generative AI Learning Repository

A comprehensive collection of Jupyter notebooks covering various generative AI topics including LangChain, LLM agents, prompt engineering, and agentic memory systems.

## Table of Contents
- [Directory Overview](#directory-overview)
- [How to Use the Notebooks](#how-to-use-the-notebooks)
- [Installation](#installation)

## Directory Overview

### 1. **ai_agents_in_langgraph**
Building simple ReAct agents from scratch using LangGraph. Covers foundational concepts for creating AI agents with OpenAI's API.

### 2. **chatgpt_prompt**
Guidelines and principles for writing effective prompts for large language models. Includes lessons on prompt development, summarizing, inferring, transforming, expanding, and building chatbots.

### 3. **functions_tools_agents_with_langchain**
Exploration of OpenAI function calling capabilities and LangChain integration. Covers LCEL (LangChain Expression Language), function calling, tagging, extraction, tools, routing, and conversational interactions.

### 4. **langchain_llm**
Comprehensive guide to LangChain fundamentals including models, prompts, output parsers, memory management, chains, Q&A systems, evaluation, and agents.

### 5. **llm_as_operating_system**
Advanced topics on using LLMs as operating systems. Includes agentic RAG systems, memory management with MemGPT and Letta, and external memory access patterns.

### 6. **long_term_agentic_memory**
Building AI assistants with long-term semantic memory. Focuses on email assistants and other applications that require remembering details from previous interactions.

### 7. **mcp**
Model Context Protocol lessons and examples, including chatbot implementations with tool definitions and execution.

## How to Use the Notebooks

1. **Prerequisites:** Ensure you have Jupyter installed and the necessary Python packages:
   ```bash
   pip install jupyter openai langchain python-dotenv anthropic
   ```

2. **API Keys:** Set up your OpenAI and other API keys in a `.env` file:
   ```
   OPENAI_API_KEY=your_key_here
   ```

3. **Running Notebooks:** 
   - Open a notebook in Jupyter: `jupyter notebook`
   - Run cells sequentially from top to bottom
   - Follow markdown instructions provided in each notebook
   - Some notebooks may include interactive components (chatbots, etc.)

4. **Downloading:** You can download notebooks locally by clicking "File" → "Download as" → "Notebook (.ipynb)"

## Installation

Clone or download this repository and navigate to the directory:

```bash
cd /home/bishal/Documents/Projects/gen_ai
```

Install required dependencies:

```bash
pip install -r requirements.txt
```

(Note: Check individual notebooks for specific package requirements)