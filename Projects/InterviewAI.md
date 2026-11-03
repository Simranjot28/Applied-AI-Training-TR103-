# InterviewAI — AI-Powered Personalized Multimodal Interview Preparation Platform

## 1. Project Overview

InterviewAI is an AI-powered interview preparation platform designed to help students and job seekers prepare for technical and HR interviews through interactive practice and personalised feedback.

The main idea behind the project was to make interview preparation more accessible, structured, and interactive by using Artificial Intelligence. Instead of depending only on static question banks or manually reviewing answers, users can practise interviews with an AI-powered interviewer and receive feedback on their responses.

The platform brings together multiple preparation modules, including resume analysis, skill gap identification, aptitude practice, AI-based interview sessions, and performance feedback.

The project was developed individually during the Applied AI training using Antigravity IDE, with the objective of applying AI concepts to a practical, real-world application.

## 2. Problem Statement

Preparing for technical and HR interviews can be challenging for students, especially those who do not have regular access to interview practice or professional guidance.

Some common difficulties include:

- Finding interview questions relevant to a particular job role.
- Understanding the skills and knowledge required for a target position.
- Identifying weaknesses through self-assessment.
- Practising technical and behavioural questions in an interview-like environment.
- Receiving useful feedback on answers and understanding how to improve them.
- Managing interview preparation through different resources and platforms.

InterviewAI addresses these challenges by bringing different interview preparation activities together in one AI-powered platform.

## 3. Project Objectives

The main objectives of InterviewAI were:

- To develop an AI-powered platform for personalised interview preparation.
- To provide technical and HR interview practice.
- To generate questions based on the selected role, company context, and difficulty level.
- To explore resume analysis and ATS-related evaluation.
- To identify skill gaps and suggest areas for improvement.
- To provide structured feedback on interview answers.
- To make interview preparation more interactive through AI-based conversations.
- To explore the practical integration of LLMs and APIs into a web application.

## 4. System Modules and Key Features

The platform was organised into different modules to cover multiple stages of interview preparation.

### 4.1 User Authentication and Student Profile

This module provides the entry point to the platform. Users can access the application through authentication and maintain their profile information.

The profile provides a foundation for organising the user's interview preparation activities.

### 4.2 Target Role Selection

Users can select the job role or position for which they want to prepare.

The selected role helps provide context for generating relevant interview questions and organising preparation activities.

### 4.3 Resume Analysis and ATS Evaluation

This module explores the use of AI to analyse uploaded resumes and provide useful information about their content.

The functionality includes examining resume details and considering how well the available information aligns with a target job role. ATS-related evaluation is intended to help users understand areas where their resumes may need improvement.

### 4.4 Skill Gap Analysis

Skill gap analysis focuses on identifying the skills that may require further development based on the user's selected role and available resume information.

It helps students understand the difference between their existing skills and the requirements associated with their target position.

### 4.5 Learning Roadmap

The learning roadmap provides direction for improving skills relevant to the selected job role.

It aims to help users organise their preparation and focus on areas that need attention.

### 4.6 Aptitude Preparation

This module supports aptitude-related preparation by providing an additional practice area for students preparing for recruitment processes.

It complements the technical and HR interview preparation modules.

### 4.7 AI Technical Interview

The AI Technical Interview module is one of the central features of InterviewAI.

It allows users to practise technical interview questions based on factors such as:

- Selected technical role.
- Company context.
- Question difficulty.
- Technical subject or knowledge area.

The AI model can generate questions and evaluate the responses provided by users.

The objective is to create a more interactive technical interview practice experience rather than simply displaying a fixed list of questions.

### 4.8 AI HR Behavioural Interview

This module focuses on behavioural and HR interview preparation.

It explores questions related to communication, teamwork, problem-solving, professional experiences, strengths, weaknesses, and workplace situations.

The AI interviewer can be used to practise responses to these questions and provide feedback to help users improve their answers.

### 4.9 Interview Feedback and Evaluation

Feedback is an important part of the interview preparation process.

The platform explores structured evaluation of user responses through different aspects:

- **Score:** A numerical assessment of the answer.
- **Strengths:** Important points that were explained well.
- **Missing Concepts:** Relevant information that could have been included.
- **Weaknesses:** Areas where the answer needs improvement.
- **Ideal Answer:** An example of a stronger and more complete response.
- **Improvement Tips:** Suggestions for answering similar questions more effectively.

The feedback is intended to help users understand their performance and learn how to improve.

### 4.10 Dashboard

The dashboard provides a central area for presenting relevant preparation information and user activity.

It helps bring together information from different modules and gives users an organised view of their interview preparation journey.

## 5. AI Concepts and Their Applications

### 5.1 Large Language Models (LLMs)

Large Language Models are used for natural-language processing and response generation.

In InterviewAI, LLM capabilities are explored for generating interview questions, understanding user responses, and producing structured feedback.

### 5.2 Gemini 2.5 Flash

Gemini 2.5 Flash was used as the AI model for the project's AI-powered functionality.

It supported the exploration and implementation of conversational features, question generation, and response-related evaluation.

### 5.3 Prompt Engineering

Prompt engineering plays an important role in guiding the AI interviewer's behaviour.

Prompts can define:

- The role of the AI as an interviewer.
- The selected job role and interview context.
- The expected difficulty of questions.
- The evaluation criteria for user responses.
- The structure and format of generated feedback.

This helps make AI responses more relevant to the interview preparation requirements.

### 5.4 API Integration

API integration connects the application with external AI services.

The project used API-based communication to access AI functionality and process requests and responses between the application and the AI model.

### 5.5 Natural Language Processing

Natural-language processing concepts are relevant to understanding user input and working with text-based interview questions and answers.

They support the broader conversational experience of the platform.

## 6. System Architecture and Technology Stack

InterviewAI follows a frontend-backend architecture in which the user interface communicates with backend services, while AI-related functionality is integrated through API-based communication.

### Frontend

- **React:** Used for building the user interface and reusable application components.
- **Vite:** Used as the frontend development and build environment.
- **Tailwind CSS:** Used for styling and designing the interface.
- **Framer Motion:** Used for interface animations and transitions.
- **Recharts:** Used for presenting information through charts and visual elements.
- **Monaco Editor:** Included as part of the application's technical functionality.

### Backend

- **Python:** Used for backend development.
- **FastAPI:** Used for building backend APIs and handling application requests.
- **SQLAlchemy:** Used for database interaction.
- **SQLite:** Used as the database for storing application data.
- **JWT Authentication:** Used for token-based authentication.
- **PyPDF2:** Used for working with PDF documents, including resume-related processing.

### AI and Additional Technologies

- **Gemini 2.5 Flash:** Used for AI-powered functionality.
- **ChromaDB:** Explored for vector database and knowledge-retrieval functionality.
- **Piston/Wandbox:** Explored for code-execution-related functionality.

## 7. Development Approach

The development of InterviewAI involved understanding the interview preparation problem, identifying the required modules, and exploring how AI could support the different functionalities.

Antigravity IDE was used as the primary development environment. The project was organised into frontend and backend components to separate the user interface from application logic and API processing.

The development approach involved the following stages:

1. **Requirement Identification:** Understanding the challenges faced by students during interview preparation and defining the project's objectives.
2. **Feature Planning:** Identifying the main modules, including authentication, resume analysis, skill gap analysis, aptitude practice, and AI interviews.
3. **Frontend Development:** Working on the user interface and organising the different application modules.
4. **Backend Development:** Exploring API endpoints, application logic, authentication, and database interaction.
5. **AI Integration:** Connecting AI functionality through Gemini 2.5 Flash and exploring prompt-based question generation and evaluation.
6. **Testing and Debugging:** Reviewing application workflows, checking feature behaviour, and identifying issues.
7. **Refinement:** Reviewing AI responses and considering improvements to the interview experience and feedback process.

## 8. Testing and Challenges

Testing was an important part of reviewing InterviewAI because the platform combined normal software functionality with AI-generated responses.

Some important testing considerations included:

- Checking whether generated questions were relevant to the selected role.
- Reviewing whether the AI evaluation was connected to the actual answer.
- Checking how the system handled incomplete or unrelated responses.
- Understanding API communication and possible integration errors.
- Reviewing the interaction between frontend and backend modules.
- Examining whether the feedback was understandable and useful to the user.

One important consideration in AI interview development was ensuring that the system did not simply move to the next question without appropriately evaluating the user's response.

This highlighted the importance of answer relevance checking and meaningful interviewer feedback.

## 9. Individual Contribution

InterviewAI was developed as an individual project during the Applied AI training.

My contribution involved exploring the project requirements, understanding the application structure, working with Antigravity IDE, and developing the platform's different functional modules.

I worked on connecting frontend and backend functionality and exploring the integration of Gemini 2.5 Flash for AI-powered interview features.

I also explored prompt engineering for generating interview questions and structuring feedback, along with reviewing the application's behaviour through testing and debugging.

The project gave me an opportunity to apply the concepts studied during training in a larger AI-integrated web application.

## 10. Learning Outcomes

Developing InterviewAI provided practical exposure to building an AI-powered application that combines web development with artificial intelligence.

Through this project, I strengthened my understanding of:

- Integrating LLMs into web applications.
- Using prompt engineering to guide AI behaviour.
- Working with APIs and frontend-backend communication.
- Understanding application architecture using React and FastAPI.
- Exploring AI-based question generation and answer evaluation.
- Organising a larger application into separate functional modules.
- Testing and debugging applications that use AI-generated responses.

The project also helped me understand that developing an AI application involves more than connecting an AI model to a user interface. It requires proper planning, application logic, prompt design, integration, testing, and continuous refinement.

Overall, InterviewAI was an important practical learning experience that helped me connect my knowledge of web development with Applied AI concepts and understand how AI can be used to address real-world problems.
