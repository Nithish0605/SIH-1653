# Smart India Hackathon Workshop
# Date: 21/3/2025
## Register Number: 212224240105
## Name: NITHISH S
## Problem Title
SIH 1653: Web based Selector-Applicant Simulation Software
## Problem Description
Background: Recruitment and Assessment Centre (RAC) under DRDO, Ministry of Defence carries out interviews for applications received against advertised vacancies and for promotion to next higher grade for scientific manpower inducted within DRDO. Description: The process of interviewing is a challenging task. An unbiased objective interviewing process helps identify the right talent. The basic process of an interview involves posing a set of questions by an interviewer and thereafter evaluating responses from candidates. Thus, the questions asked should be relevant and match the area/ expertise of the applicant and the responses should also be of relevance w.r.t. the question asked. Expected Solution: The proposed solution should provide experts as well as candidates a real life Board Room experience, starting with initial ice-breaking questions leading to in-depth techno-managerial (depending on the level of candidate) questions. It shall also be able to provide a quantifiable score for experts as well as the candidate for the relevancy of questions w.r.t. the area/ expertise of the applicant. Similarly, candidate responses should also be graded for relevancy w.r.t. the question asked, finally assisting in arriving at an overall score for the subject knowledge of the candidate and thus his/ her suitability against the advertised post.

## Problem Creater's Organization
Ministry of Defence

## Idea
To create a web-based platform that simulates a real-life boardroom interview experience, ensuring an objective and efficient selection process. This platform will leverage Artificial Intelligence (AI) to dynamically select questions and grade candidate responses. The system will reduce human biases, provide insightful feedback, and enhance the overall interview process for both selectors and applicants.

## Proposed Solution / Architecture Diagram
Proposed Solution:

To address the challenges, we propose a Web-based Selector-Applicant Simulation Software that:

Simulates Real-Life Board Room Interviews:

Provides an interactive virtual environment replicating a real-life boardroom.

Supports structured interview flows, beginning with ice-breaking questions and advancing to detailed techno-managerial discussions.

Automates Question Matching:

Uses AI to dynamically select questions based on the candidate’s expertise and the advertised role.

Automates Response Grading:

Leverages Natural Language Processing (NLP) to evaluate candidate responses for relevance, clarity, and technical depth.

Grades questions posed by experts to assess their alignment with the candidate’s domain.

Provides Quantifiable Scores:

Generates objective scores for candidates based on their subject knowledge and responses.

Assesses experts’ questioning for relevancy and consistency.

Offers Feedback and Analytics:

Generates post-interview reports for candidates to identify strengths and weaknesses.

Provides performance insights for interview panels to enhance their questioning techniques.



The architecture consists of the following components:

Frontend:

Built using React.js for interactivity and responsiveness.

Features real-time feedback, scoring visualization, and interview simulation tools.

Backend:

Developed using Node.js or Django for robust API management and business logic.

Handles interview flow, question matching, and scoring algorithms.

AI/NLP Engine:

Utilizes frameworks like Hugging Face Transformers, spaCy, or OpenAI APIs.

Supports semantic matching for questions and evaluates candidate responses.

Database:

Relational database (PostgreSQL or MySQL) for structured data storage.

Stores user profiles, questions, responses, and scoring data.

Deployment:

Hosted on cloud platforms like AWS, Azure, or Google Cloud for scalability.

Implements containerization with Docker and CI/CD pipelines for continuous updates.


![Screenshot 2025-03-21 102212](https://github.com/user-attachments/assets/5715f17b-3f17-44c2-bc74-8e5ca2ae3adc)

## Use Cases
Interview Simulation:

Simulates a structured boardroom interview for candidates.

Dynamically adjusts question complexity based on the candidate’s responses.

Question Relevance Evaluation:

Ensures experts’ questions align with the candidate’s area of expertise.

Response Scoring:

Automatically grades candidate responses for clarity, relevance, and subject depth.

Feedback Generation:

Provides candidates with actionable feedback to improve their performance.

Panel Insights:

Helps interviewers analyze their questioning approach and improve objectivity.

![Screenshot 2025-03-21 102419](https://github.com/user-attachments/assets/e2c76192-720e-4d56-a78c-921c69afbce3)


## Technology Stack

Frontend:

Framework: React.js, Tailwind CSS for styling.

Real-time updates using WebSocket.

Backend:

Framework: Node.js with Express.js or Django.

APIs: RESTful or GraphQL for communication.

AI/ML:

NLP Models: BERT, GPT, or spaCy for question-response matching and evaluation.

Libraries: Transformers, TensorFlow, PyTorch.

Database:

Relational: PostgreSQL or MySQL.

Optional: MongoDB for semi-structured data storage.

Cloud Hosting:

Platforms: AWS, Azure, or Google Cloud.

CI/CD: Jenkins or GitHub Actions for continuous integration.

![Screenshot 2025-03-21 103116](https://github.com/user-attachments/assets/7ca6fda3-82da-4622-ad41-a9b11bd611e3)



## Dependencies

Pre-trained Models:

Domain-specific question-response datasets for training and fine-tuning.

Cloud Infrastructure:

Compute and storage resources for handling AI workloads and user data.

Third-party APIs:

Authentication: OAuth2 or JWT.

NLP Services: Hugging Face, OpenAI API for advanced NLP tasks.

Security Measures:

SSL/TLS for encrypted communication.

Role-based access control (RBAC) for secure data handling.

![web app](https://github.com/user-attachments/assets/5f436dd7-a694-45d1-81d2-8386a2037205)


