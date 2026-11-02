# Day 13 — MCP, A2A, and Multi-Agent Systems

## 1. Objective

The objective of this session was to understand how AI systems connect with external tools and how multiple AI agents can communicate and collaborate on complex tasks. The session introduced Model Context Protocol (MCP), Agent-to-Agent (A2A) communication, and multi-agent architectures. These concepts help explain how AI applications can integrate external services and coordinate specialized tasks.

## 2. Topics Covered

### Model Context Protocol (MCP)

Model Context Protocol (MCP) is an open protocol designed to provide a standardized way for AI applications to connect with external tools, data sources, and other services. It helps reduce the need to create a separate integration approach for every supported tool.

Through MCP, an AI application can interact with capabilities exposed by an MCP server. Depending on the server, these capabilities may include tools that perform operations, resources that provide data, or prompts that supply reusable instructions.

For example, an AI assistant could connect to an MCP server that exposes approved functions for searching documents or retrieving information from a database. The assistant can then use these capabilities as part of a larger workflow, subject to the permissions and controls of the application.

MCP is useful because it standardizes aspects of connecting AI applications with external capabilities. It does not, by itself, guarantee that every connected tool is safe or that the model will always use it correctly.

### Agent-to-Agent (A2A) Communication

Agent-to-Agent (A2A) is a protocol designed to support communication and collaboration between AI agents, including agents built using different systems or frameworks.

In a multi-agent workflow, one agent may be responsible for research, another for analysis, and another for preparing a final result. A2A provides a standardized approach for agents to discover capabilities and exchange information or delegate tasks, depending on the implementation.

For example, in a career-guidance workflow, one agent could gather information about a student's interests, while another could help organize suitable career options. A coordinating component could then combine the results into a response.

A2A focuses on communication and collaboration between agents, rather than the connection between an AI application and an external tool.

### Multi-Agent Systems

A multi-agent system consists of multiple agents that work together to accomplish a shared objective or handle different parts of a larger task. Each agent may have a specific role, instructions, tools, or area of responsibility.

Common arrangements include:

- **Sequential workflow:** Agents complete tasks in a defined order.
- **Parallel workflow:** Multiple agents handle separate tasks at the same time.
- **Coordinator-based workflow:** A central component assigns tasks and combines the results.
- **Specialized agents:** Different agents focus on tasks such as research, coding, analysis, or summarization.

Multi-agent systems can help divide complex tasks into manageable parts. However, they also introduce challenges such as communication overhead, conflicting outputs, duplicated work, and the need to validate the combined result.

### Difference Between MCP and A2A

MCP and A2A address different integration needs. MCP focuses on connecting AI applications with external tools and context, while A2A focuses on communication and collaboration between agents.

Both can be relevant in a larger AI architecture. An agent may use MCP to access a tool or data source and use an A2A-based mechanism to collaborate with another agent. The exact design depends on the requirements of the application.

## 3. Research and Practical Work

During this session, I researched MCP and A2A and explored how they support different forms of connectivity in AI systems. I examined the distinction between connecting an AI application to an external capability and enabling two agents to exchange information or delegate tasks.

As part of the practical exploration, I considered a multi-agent career-guidance scenario in which specialized agents handle different responsibilities. For example, one agent could focus on understanding a student's interests, while another could organize relevant career information. Their outputs could then be combined into a final response.

I also explored how a tool-enabled agent could access information through an external service and how standardized protocols can make integrations easier to organize. The importance of access permissions, clear task boundaries, and checking results from different agents was considered.

This session helped me understand how AI architectures can move beyond a single model and support coordinated workflows involving tools, external information, and multiple agents.

## 4. Tools and Technologies

- **Model Context Protocol (MCP):** Studied for connecting AI applications with external tools and data.
- **Agent-to-Agent (A2A):** Explored for communication and collaboration between AI agents.
- **Multi-agent systems:** Studied for dividing complex tasks among specialized agents.
- **APIs and integrations:** Considered for connecting different software components.
- **Workflow orchestration:** Learned how multiple tasks and agent outputs can be coordinated.

## 5. Learning Outcomes

By the end of this session, I understood the purpose of MCP and A2A and the different problems they are designed to address. I learned how MCP supports access to external tools and context, while A2A supports communication between agents.

I also gained an understanding of multi-agent workflows, including sequential execution, parallel tasks, and coordinator-based arrangements. These concepts broadened my understanding of AI system architecture and prepared me to explore AI security, quality assurance, and testing practices.
