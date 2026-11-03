# Day 23 — InterviewAI: Testing, Debugging, and Feature Validation

## 1. Objective

The objective of this session was to test and review the functionality of InterviewAI, an AI-powered interview preparation platform. After exploring the main features and AI integration, the focus shifted towards checking the application's behaviour, identifying possible issues, and understanding how individual modules contribute to the overall user experience.

## 2. Topics Covered

### Importance of Testing an AI-Based Application

Testing is an important stage of application development because it helps identify errors and verify whether the implemented features behave as expected.

In an AI-powered application, testing involves more than checking whether a feature opens or produces an output. It is also necessary to examine the relevance, accuracy, and usefulness of AI-generated responses.

For InterviewAI, testing considerations included:

- Whether the interview questions match the selected role and difficulty.
- Whether the AI responds appropriately to user answers.
- Whether the feedback is relevant to the question and answer.
- Whether the different modules follow the intended workflow.
- Whether the interface provides a clear and understandable user experience.

### Functional Testing

Functional testing focuses on checking whether an application performs its intended tasks.

For InterviewAI, the main areas to review included authentication, role selection, resume-related functionality, interview practice, and feedback generation.

Checking these features helps identify problems in the interaction between different parts of the application.

### Debugging and Error Identification

Debugging is the process of identifying, analysing, and correcting errors in software. Issues can occur in the frontend, backend, API communication, or AI response-generation process.

In an AI-integrated application, it is also important to distinguish between a technical error and an issue with the quality of the generated response.

For example, an API connection issue may prevent a response from being generated, whereas an irrelevant answer may indicate a problem with the prompt or evaluation logic.

### Validation of AI-Generated Feedback

The quality of AI-generated feedback is particularly important in an interview preparation platform.

A useful evaluation should consider whether the user's answer is related to the question, whether important concepts are covered, and whether the feedback provides practical suggestions.

An interview system should not automatically treat every submitted response as acceptable. It should identify unrelated or incomplete answers and communicate the issue clearly to the user.

## 3. Research and Practical Work

During this session, I explored the testing and debugging considerations involved in InterviewAI. I reviewed the importance of checking the platform's main features and understanding how the frontend, backend, and AI functionality work together.

I also considered different interview scenarios to understand how the AI interviewer should behave when users provide correct, incomplete, or unrelated answers. Particular attention was given to the feedback process because it directly affects the usefulness of the interview practice experience.

This session helped me understand that an AI-based application requires both functional testing and evaluation of AI response quality. It also highlighted the importance of identifying issues before considering a feature ready for demonstration.

## 4. Tools and Technologies

- **Antigravity IDE:** Used for development and reviewing project code.
- **React and Vite:** Used for the frontend application.
- **Python and FastAPI:** Used for backend functionality.
- **Gemini 2.5 Flash:** AI model used for question generation and response-related functionality.
- **API testing and debugging:** Explored for identifying communication and application issues.
- **Test scenarios:** Considered for reviewing interview workflows and AI-generated feedback.

## 5. Learning Outcomes

By the end of this session, I gained a better understanding of the importance of testing and debugging in AI-integrated applications. I learned that an application must be evaluated at both the software-functionality level and the AI-response level.

I also understood why answer relevance, feedback quality, and correct handling of incomplete or unrelated responses are important in an AI interview system. This session provided useful insights for the final review and refinement of InterviewAI.
