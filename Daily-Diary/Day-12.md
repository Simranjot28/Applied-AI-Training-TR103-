# Day 12 — Agentic AI, AI Agents, Tools, and Orchestration

## 1. Objective

The objective of this session was to understand Agentic AI and how AI agents can work towards a goal by selecting actions, using tools, and handling multi-step tasks. The session introduced the basic architecture of AI agents, tool calling, task planning, and orchestration. It also explored the difference between a traditional AI chatbot and an agent-based system.

## 2. Topics Covered

### Understanding Agentic AI

Agentic AI refers to AI systems designed to pursue a goal through a sequence of steps rather than simply generating a response to a single prompt. Depending on their design, these systems may interpret a task, decide what action to take next, use available tools, examine the results, and continue until a defined condition is reached.

For example, a student-support assistant could help a student prepare for an interview by identifying the target role, retrieving relevant preparation material, and organizing suggested practice activities. Each step contributes to the overall objective.

The degree of autonomy varies between systems. Some agents follow predefined workflows, while others can choose between available tools or adapt their next action according to previous results.

### AI Agents and Their Components

An AI agent is a system that uses an AI model and other components to perform tasks towards a specified goal. Its design may include instructions, an LLM, available tools, context or memory, and mechanisms for evaluating the results of its actions.

The main components commonly include:

- **Goal and instructions:** Define what the agent is expected to achieve.
- **AI model:** Helps interpret requests and determine suitable actions.
- **Tools:** Allow the agent to interact with external services or perform supported operations.
- **Context or memory:** Supplies relevant information from the current task or previous interactions.
- **Feedback and evaluation:** Help determine whether the result is suitable or another step is required.

Not every AI agent includes all these components, and the exact architecture depends on the application.

### Tool Calling

Tool calling allows an AI system to request an operation from an external function, API, or service. Instead of relying entirely on generated text, the model can select an available tool when the task requires information or an action.

For example, an assistant may use a search tool to retrieve information, call an API to obtain data, or execute a supported calculation. The application runs the requested tool and provides its result back to the model, which can then continue processing the task.

Tool calling is useful because it connects language-model reasoning with capabilities provided by external systems. However, tool permissions, input validation, and error handling remain important for safe and reliable operation.

### Planning and Orchestration

Planning involves breaking a larger task into smaller steps that can be completed in a suitable order. Orchestration coordinates these steps and manages the interactions between models, tools, and other components.

For example, an AI research workflow might first identify a question, retrieve relevant information, summarize the results, and then prepare a final response. Orchestration determines how these stages connect and what happens if a step fails or produces an unsuitable result.

A well-designed workflow should define its task boundaries, handle errors, and include appropriate checks before taking important actions.

### Traditional Chatbots vs. Agent-Based Systems

A traditional chatbot generally responds to user messages through a conversational interface. An agent-based system can additionally use tools and execute a sequence of actions to accomplish a task.

The distinction is not absolute: chatbots can use tools, and agents can communicate through chat interfaces. The important difference is the system's ability to coordinate actions towards a goal rather than only produce conversational responses.

## 3. Research and Practical Work

During this session, I researched the concept of Agentic AI and explored how AI agents can be designed to handle tasks that require multiple steps. I examined examples involving tool usage, task planning, and coordination between an AI model and external services.

As part of the practical exploration, I considered a workflow in which an AI assistant receives a goal, identifies the required steps, uses an appropriate tool when needed, and evaluates the result before continuing. This helped illustrate how an agent-based application differs from a system that only generates a direct text response.

I also explored the role of orchestration in connecting multiple operations into a complete workflow. The importance of validating tool inputs, managing errors, and checking the final output was considered as part of understanding reliable agent design.

This session helped connect earlier topics such as LLMs, prompting, and APIs with more advanced AI application architectures.

## 4. Tools and Technologies

- **Large Language Models (LLMs):** Studied as the decision-making component in agent-based systems.
- **AI agents:** Explored for goal-oriented, multi-step task execution.
- **Tool calling:** Studied for connecting models with functions and external services.
- **APIs:** Considered for enabling agents to access external capabilities.
- **Orchestration:** Learned how to coordinate tasks and manage workflow steps.

## 5. Learning Outcomes

By the end of this session, I understood the basic concepts of Agentic AI and how AI agents can use tools to work towards defined goals. I learned about the roles of instructions, models, tools, context, and evaluation in an agent-based system.

I also gained an understanding of task planning and orchestration and how these concepts help coordinate multiple operations. This knowledge provides a foundation for exploring more advanced topics, including multi-agent systems and communication protocols such as MCP and A2A.
