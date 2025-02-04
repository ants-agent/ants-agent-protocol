# Ants AI Agent Protocol


## Overview

The Ants AI Agent Protocol is a protocol for building AI agents that can interact with each other.  Because the output of AI models is often fuzzy and not in the correct format, we will use the zod `parse` method to parse the output of the AI model. For the future of python version, we will use the pydantic `from_json` method to parse the output of the AI model.

We will initially use the langchainjs to build the agents. By that way, we can enjoy the initial design of the task schema and task orchestration. After that, we will migrate the code to a more crypto-native version to provide a better adaption to the crypto-native environment. In the end, we will provide the following features:

- [ ] Crypto-native agents
- [ ] Crypto-native task orchestration
- [ ] Crypto-native task schema
- [ ] Crypto-native tool schema
- [ ] Crypto-native tool invocation
- [ ] Crypto-native tool result
- [ ] Async Agent for better performance
- [ ] Agentic loop for better task orchestration

For each schema of Agent, we can follow the usage in [this link](https://langchain-ai.github.io/langgraphjs/tutorials/workflows/#building-blocks-the-augmented-llm)

## Core Concepts

### Agents

Agents are the main building blocks of the Ants AI Agent Protocol. They are responsible for executing tasks and communicating with other agents.

### Tasks

Tasks are the smallest unit of work in the Ants AI Agent Protocol. They are responsible for executing a single task and communicating with other agents.

### Tools

Tools are the smallest unit of work in the Ants AI Agent Protocol. They are responsible for executing a single task and communicating with other agents.







