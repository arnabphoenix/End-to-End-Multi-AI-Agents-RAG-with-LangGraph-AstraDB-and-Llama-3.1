# Multi-AI Agent System

This project showcases a multi-agent AI architecture where each AI agent specializes in a specific task, collaborating in an end-to-end application powered by LangChain and Graph AI concepts. The system leverages multiple agents to create a robust, scalable, and versatile application capable of handling complex data flows and interactions.

### Key Features
- **Distributed AI Agents**: Each AI agent is designed for a specific task, such as:
  - **Data Retrieval from AstraDB**: One agent connects to AstraDB, querying and retrieving data as needed.
  - **Wikipedia Search**: Another agent connects to Wikipedia to fetch relevant information based on the context.
- **Inter-Agent Communication**: All agents work collaboratively, sharing and processing information to achieve a common goal.
- **Conditional Edges and Nodes**: The architecture employs a graph-based approach where nodes represent the AI agents and edges signify the communication pathways between them. Conditional edges dictate the flow based on task requirements, ensuring seamless interaction and optimized processing.

### Application Overview

The multi-AI agent system integrates the agents to form a cohesive workflow:
1. **Task Assignment**: Each agent is assigned a distinct function, allowing efficient parallel processing.
2. **Data Gathering and Processing**: Agents perform data retrieval and enrichment from external sources (e.g., AstraDB, Wikipedia).
3. **Conditional Routing**: Based on task conditions, data flow is controlled via conditional edges, making the system adaptable and responsive.
4. **End-to-End Workflow**: The agents work in synergy to provide an end-to-end solution, demonstrating the power of multi-agent collaboration.

### Requirements

This project requires the following libraries and APIs to function properly:
- **GroqAPI**
- **Huggingface**
- **Datastax**

Make sure to install these dependencies before running the application.
