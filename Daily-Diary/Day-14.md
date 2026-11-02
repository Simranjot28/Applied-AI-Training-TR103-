# Day 14 — AI Security, Prompt Injection, and Quality Assurance

## 1. Objective

The objective of this session was to understand important security challenges associated with AI-powered applications and learn how quality assurance practices help improve their reliability. The session focused on prompt injection, sensitive data exposure, access control, and testing AI-generated responses. It also provided an opportunity to review the concepts covered during the first phase of Applied AI training.

## 2. Topics Covered

### AI Security Fundamentals

AI security involves protecting AI systems, their data, connected tools, and users from misuse or unauthorized access. AI applications may interact with external APIs, process user-provided information, retrieve documents, or execute tool calls, making security an important part of their design.

A security issue can affect not only the AI model but also the surrounding application. For example, an application may expose sensitive information if permissions are not configured correctly or may perform an unintended action if tool inputs are not properly validated.

We explored the importance of protecting credentials, limiting access to sensitive information, validating user inputs, and applying appropriate security controls throughout an AI workflow.

### Prompt Injection

Prompt injection is a type of attack in which malicious or manipulative input attempts to influence an AI system to ignore its intended instructions or behave in an unintended way.

For example, a user might submit a message asking an AI assistant to disregard its original task and reveal information it should not disclose. Similar risks can arise from untrusted content retrieved from documents or external sources.

Prompt injection is particularly relevant to AI applications that use RAG, process external content, or connect to tools. Retrieved text should be treated as data rather than automatically trusted instructions.

Some useful safeguards include:
- Clearly separating trusted instructions from untrusted content.
- Restricting tools and actions to the permissions actually required.
- Avoiding the inclusion of unnecessary sensitive information in prompts.
- Validating tool inputs and checking important actions.
- Testing the application with unexpected or adversarial inputs.

No single safeguard eliminates every prompt-injection risk, so multiple layers of protection are important.

### Data Privacy and Access Control

AI applications may handle personal information, API credentials, documents, or other sensitive data. Data privacy focuses on protecting this information and ensuring it is used appropriately.

Access control determines which users or components can access particular resources or perform specific actions. Role-based access control (RBAC), for example, assigns permissions according to a user's role.

For an educational assistant, students and administrators may require different permissions. The application should enforce these permissions through its backend and supporting services rather than relying only on the AI model to decide what information may be disclosed.

We also considered secure credential handling and the importance of avoiding unnecessary exposure of confidential information.

### Quality Assurance and AI Testing

Quality assurance (QA) involves evaluating whether a software application behaves as expected and meets its requirements. For AI applications, testing includes both ordinary software functionality and the quality of generated responses.

Important areas of AI testing include:

- **Functional testing:** Checking whether features work as intended.
- **Relevance testing:** Evaluating whether responses address the user's question.
- **Accuracy checks:** Identifying incorrect or unsupported information.
- **Negative testing:** Checking how the application responds to invalid or unexpected inputs.
- **Security testing:** Evaluating whether sensitive information or restricted actions can be accessed improperly.
- **Consistency testing:** Comparing outputs across different inputs and repeated tests where appropriate.

AI systems can produce variable outputs, so evaluation should consider the application's requirements rather than relying only on whether the response sounds convincing.

## 3. Research and Practical Work

During this session, I researched security challenges associated with AI applications and explored examples of prompt injection and potentially unsafe model behavior. I considered how malicious instructions, untrusted documents, and insufficient access controls could affect an AI assistant.

As part of the practical exploration, I reviewed scenarios involving unexpected user inputs and considered how an application should respond when a request is irrelevant, invalid, or attempts to access restricted information. I also explored the importance of keeping API credentials private and limiting the permissions granted to external tools.

I examined QA practices for AI-powered applications, including checking response relevance, identifying incorrect outputs, and evaluating how an application handles errors. These concepts highlighted the need to test both the AI-generated responses and the surrounding software functionality.

Finally, I reviewed the main topics covered during the first phase of training, including LLMs, prompt engineering, APIs, embeddings, vector databases, RAG, and Agentic AI. This review helped connect the individual concepts into a broader understanding of AI application development.

## 4. Tools and Technologies

- **AI security concepts:** Studied prompt injection and sensitive-data risks.
- **Access control:** Explored permissions and role-based access principles.
- **Quality assurance:** Reviewed functional, negative, and response-quality testing.
- **APIs and credentials:** Considered secure integration practices.
- **LLMs and RAG:** Reviewed common security and reliability challenges in AI workflows.

## 5. Learning Outcomes

By the end of this session, I understood why security and quality assurance are important when developing AI-powered applications. I learned about prompt injection, data privacy, access control, and the need to validate inputs and restrict tool permissions.

I also gained an understanding of how AI applications can be tested for functionality, relevance, accuracy, consistency, and security. Completing this phase helped me connect the theoretical concepts studied during training and prepared me to apply relevant ideas in practical project work.
