# Day 5 — Zero-Shot, Few-Shot, and Role-Based Prompting

## 1. Objective

The objective of this session was to understand different prompting techniques used with Large Language Models and learn how to guide a model toward more relevant and structured responses. The session focused on zero-shot prompting, few-shot prompting, and role-based prompting, along with practical ways to select and refine these techniques according to the task requirements.

## 2. Topics Covered

### Zero-Shot Prompting

Zero-shot prompting is a technique in which a model is given an instruction or question without any examples of the expected answer. The model uses its previously learned patterns and the information provided in the prompt to generate a response.

This technique is useful for straightforward tasks such as answering general questions, translating text, summarizing information, or explaining technical concepts. Its effectiveness depends on how clearly the task is described and whether the model has sufficient knowledge to respond appropriately.

For example, the prompt *"Classify this review as positive or negative: 'The service was excellent'"* asks the model to perform a task without providing sample classifications.

### Few-Shot Prompting

Few-shot prompting involves including a small number of examples in the prompt to demonstrate the expected task and output pattern. These examples help the model understand the desired format or classification approach without requiring additional model training.

For example, a prompt may include examples of positive and negative product reviews with their corresponding labels before asking the model to classify a new review. This can be useful when a task requires a specific response structure or a consistent style.

The quality and relevance of the examples are important because unclear or inconsistent examples may lead to unsuitable outputs.

### Role-Based Prompting

Role-based prompting involves instructing an AI model to respond from a particular role or perspective. The role provides context about the expected tone, level of detail, and type of assistance.

For example, asking the model to *"Act as a career counselor and explain suitable career paths for a computer science student"* establishes a clear context for the response.

This technique can be useful for educational assistants, interview preparation tools, career-guidance chatbots, and technical support systems. However, assigning a role does not guarantee factual accuracy, so the generated information still needs to be evaluated.

## 3. Research and Practical Work

During this session, I researched the differences between zero-shot, few-shot, and role-based prompting and explored how each technique can be applied to different tasks. I examined how the presence of examples and role instructions can influence the structure, tone, and relevance of AI-generated responses.

As part of the practical exploration, I considered example prompts for tasks such as sentiment classification, technical explanations, and career guidance. I compared a direct instruction with prompts containing sample input-output pairs or a clearly defined role to understand their different purposes.

For example, a zero-shot prompt can directly ask an AI model to classify a review. A few-shot prompt can provide two or three labeled reviews before asking it to classify another one. A role-based prompt can instruct the model to act as a career advisor and explain possible career options in simple language.

This exploration helped me understand that prompting techniques should be selected according to the task. Simple instructions may be sufficient for straightforward questions, while examples can be useful for consistent formatting, and role-based instructions can help establish an appropriate response style.

## 4. Tools and Technologies

- **Large Language Models (LLMs):** Explored model responses to different instructions.
- **Zero-shot prompting:** Studied task execution without examples.
- **Few-shot prompting:** Examined the use of sample input-output pairs.
- **Role-based prompting:** Explored role and persona instructions.
- **AI-powered conversational tools:** Used for prompt-based exploration.

## 5. Learning Outcomes

By the end of this session, I developed an understanding of three important prompting techniques and their practical applications. I learned how zero-shot prompting supports direct instructions, how few-shot prompting uses examples to demonstrate the expected output, and how role-based prompting establishes a particular perspective or communication style.

I also understood that no single prompting technique is best for every situation. Selecting an appropriate approach depends on the complexity of the task, the need for examples, the desired output format, and the level of guidance required from the model.
