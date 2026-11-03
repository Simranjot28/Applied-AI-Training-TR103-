# Day 22 — InterviewAI: AI Integration and Interview Module Development

## 1. Objective

The objective of this session was to explore the integration of AI functionality into InterviewAI, with particular attention to its interview practice module. The focus was on understanding how an AI interviewer could generate relevant questions, interact with users, evaluate their answers, and provide meaningful feedback.

## 2. Topics Covered

### AI Integration in InterviewAI

AI integration was one of the most important aspects of the project because it enabled the platform to provide more than static interview questions.

Large Language Models (LLMs) can process natural-language instructions and generate responses based on the context provided. In InterviewAI, this capability was explored for creating interview questions and analysing user responses.

The project used Gemini 2.5 Flash as the AI model for its conversational and response-generation functionality.

### AI-Based Question Generation

An interview preparation platform should generate questions that are relevant to the user's preparation goals. The questions can vary depending on factors such as:

- Selected technical or professional role.
- Company or interview context.
- Difficulty level.
- Technical or HR interview category.

Prompt engineering helps provide these details to the AI model so that the generated questions are better aligned with the user's requirements.

### Answer Evaluation and Feedback

Generating questions is only one part of an AI interview system. Another important feature is evaluating the answers provided by users.

The feedback process was explored around the following aspects:

- **Answer relevance:** Whether the response addresses the question.
- **Correctness:** Whether the important concepts are explained accurately.
- **Strengths:** Identifying the useful points included in the answer.
- **Missing concepts:** Highlighting important information that was not covered.
- **Improvement suggestions:** Providing guidance for constructing a better answer.

A structured evaluation approach can help students understand not only whether an answer is good, but also how it can be improved.

### Prompt Engineering for the AI Interviewer

The AI interviewer needs clear instructions about its role, the type of questions it should ask, and how it should evaluate responses.

Prompt engineering was relevant to defining these instructions and guiding the AI to maintain a consistent interview experience. It also helped establish the expected structure of the feedback provided after an answer.

## 3. Research and Practical Work

During this session, I explored the AI integration requirements of InterviewAI and worked on understanding how the AI model could support the interview practice workflow.

Using Gemini 2.5 Flash for AI-based functionality, I explored how prompts could be structured to generate interview questions and produce feedback based on user responses. I also considered how the selected role, company context, and difficulty level could influence the questions.

Particular attention was given to answer evaluation. I explored why an interview system should check whether an answer is actually related to the question instead of simply accepting every response and continuing automatically.

This work helped connect concepts such as LLMs, prompt engineering, and response evaluation with a practical interview preparation application.

## 4. Tools and Technologies

- **Antigravity IDE:** Used for project development.
- **Gemini 2.5 Flash:** AI model used for question generation and response-related functionality.
- **Prompt engineering:** Used to guide question generation and evaluation.
- **React and Vite:** Frontend technologies used in the project.
- **Python and FastAPI:** Used for backend application functionality.
- **Conversational AI:** Applied to the AI interview practice workflow.

## 5. Learning Outcomes

By the end of this session, I gained a better understanding of how an LLM can be integrated into an application to support interactive interview practice. I learned how prompt instructions can influence question generation and how structured feedback can make AI-based learning more useful.

I also understood the importance of evaluating the relevance and quality of a user's answer before moving forward in an interview session. This session strengthened my understanding of the practical challenges involved in developing an AI-powered interview preparation platform.
