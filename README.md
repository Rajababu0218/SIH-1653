# Smart India Hackathon Workshop
# Date:04-03-2025
## Register Number:212224230202
## Name:Pralayakaveri Raja
## Problem Title
SIH 1653: Web based Selector-Applicant Simulation Software
## Problem Description
Background: Recruitment and Assessment Centre (RAC) under DRDO, Ministry of Defence carries out interviews for applications received against advertised vacancies and for promotion to next higher grade for scientific manpower inducted within DRDO. Description: The process of interviewing is a challenging task. An unbiased objective interviewing process helps identify the right talent. The basic process of an interview involves posing a set of questions by an interviewer and thereafter evaluating responses from candidates. Thus, the questions asked should be relevant and match the area/ expertise of the applicant and the responses should also be of relevance w.r.t. the question asked. Expected Solution: The proposed solution should provide experts as well as candidates a real life Board Room experience, starting with initial ice-breaking questions leading to in-depth techno-managerial (depending on the level of candidate) questions. It shall also be able to provide a quantifiable score for experts as well as the candidate for the relevancy of questions w.r.t. the area/ expertise of the applicant. Similarly, candidate responses should also be graded for relevancy w.r.t. the question asked, finally assisting in arriving at an overall score for the subject knowledge of the candidate and thus his/ her suitability against the advertised post.

## Problem Creater's Organization
Ministry of Defence

## Idea
```
1. AI-Powered Interview Simulation Platform:
(i) Develop an AI-powered interview platform that provides a real-life simulation of a boardroom experience for both experts and candidates. The platform will guide interviews from ice-breaking questions to in-depth techno-managerial inquiries based on the applicant’s expertise and the level of the position. This simulation will also help to create a bias-free environment for interviewers, ensuring that only relevant questions are asked, based on the candidate's skills and background.
(ii) The platform will allow candidates to experience real-time scoring, feedback, and assessments for each question based on their responses and will help interviewers in assessing the relevance of questions and answers objectively.

2. Question Relevancy Scoring System:
(i) Build a dynamic question relevancy scoring system where both the interviewer’s questions and the candidate's responses are evaluated for relevance and alignment with the applicant's field of expertise. Using Natural Language Processing (NLP) and machine learning models, the platform will provide an automatic, quantifiable score for each response.
(ii) This system will also provide real-time feedback on how relevant the interview questions are, ensuring interviewers remain aligned with the job role's requirements, reducing bias, and improving decision-making.

3. Expert Evaluation & Feedback Portal:
(i) Develop a portal where expert interviewers can provide feedback and score the relevancy of questions and responses post-interview. This feedback will be categorized based on various factors such as the depth of knowledge, critical thinking, and applicability to the advertised position.
(ii) The platform will generate an overall assessment score combining both qualitative feedback and quantitative scores to assist in making the final recruitment or promotion decision.

4. Candidate Skill Mapping and Gap Analysis:
(i) Create a candidate skill mapping tool that will allow interviewers to evaluate the applicant’s skillset, identify gaps, and assess subject knowledge based on responses. The platform will map the candidate's qualifications, previous experiences, and areas of expertise to the interview questions in real-time.
(ii) The tool will then suggest targeted questions or areas that require further exploration, ensuring comprehensive evaluation and helping interviewers align their questions with the actual needs of the position.

5. Real-Time Candidate Assessment Dashboard:
(i) Design a dashboard for real-time assessment of the candidate during the interview process. This dashboard will show the relevance scores of both questions and responses, providing interviewers with a clear view of the applicant’s strengths and weaknesses as the interview progresses.
(ii) The dashboard will also include instant feedback on how the candidate’s answers align with job requirements, enabling a more data-driven and objective decision-making process.

6. Post-Interview Data Analytics and Reporting:
(i) Integrate an advanced analytics system that collects and analyzes data from the interviews, such as the time spent on each question, response relevance, and the consistency of answers. This will help identify patterns, track progress, and assess the effectiveness of the interviewing process over time.
(ii) The system will generate detailed reports on each interview, summarizing the candidate's overall performance, the relevancy of their responses, and the interviewer’s effectiveness, which can be used for further refinement of the recruitment process.

7. Customizable Interview Question Bank:
(i) Develop a customizable question bank that interviewers can tailor to each candidate based on the role, expertise, and level of experience required. The question bank will be continuously updated based on industry trends, job requirements, and feedback from previous interviews.
(ii) Interviewers can select questions from predefined categories, such as technical skills, problem-solving, and managerial expertise, ensuring that each interview is customized for the applicant’s profile.

8. Interview Simulation for Skill Development:
(i) Implement an interactive interview simulation feature for candidates to practice before their actual interview. The platform will simulate various real-world interview scenarios based on the applicant's role, allowing them to receive feedback on their responses and improve their performance.
(ii) Candidates can also review their answers, see how their responses would have been scored, and get guidance on how to improve the relevancy of their answers for real interviews.

```

## Proposed Solution / Architecture Diagram
![WhatsApp Image 2025-03-04 at 23 05 45_fb28d83b](https://github.com/user-attachments/assets/c1e45471-a18f-483b-8ff1-8f726b4235ef)


## Use Cases
![WhatsApp Image 2025-03-04 at 23 15 40_d61a315a](https://github.com/user-attachments/assets/0c587077-ae41-48df-b9b2-950c64d66714)




## Technology Stack
```
1. Frontend (User Interface):
React.js: A JavaScript library for building dynamic, interactive user interfaces. It enables the creation of reusable components, making the app more modular and easier to manage.
Redux: A state management tool for React that helps maintain and manage application state across multiple components, ensuring a consistent flow of data in the application.
Bootstrap: A front-end framework for building responsive, mobile-first web pages quickly. It provides pre-built styles and components, ensuring a consistent and professional UI design.

2. Backend (Server-Side Logic):
Node.js: A JavaScript runtime environment that allows the execution of JavaScript code server-side. It’s well-suited for building fast, scalable applications and can handle numerous concurrent connections, making it ideal for a real-time interview system.
Express.js: A minimal and flexible Node.js web application framework that helps build robust APIs and manage HTTP requests. It provides routing, middleware support, and integrates seamlessly with Node.js.
GraphQL: A query language for APIs that enables clients to request specific data they need, ensuring optimized and flexible communication between the client and the server. Unlike REST, GraphQL allows for fetching only the relevant data needed, which enhances performance and efficiency.

3. Database (Data Storage):
MongoDB (NoSQL): A NoSQL database that stores data in flexible, JSON-like documents. It’s great for handling unstructured data, such as user activity logs, session data, and non-relational content like feedback or messages. MongoDB’s scalability makes it ideal for large amounts of data generated in real-time scenarios.
PostgreSQL (SQL): A powerful, open-source relational database management system. It’s suitable for structured data, such as storing candidate profiles, interview records, job postings, and event registrations, where data integrity and complex querying capabilities are essential.

4. Authentication & Security:
JWT (JSON Web Tokens): A compact, URL-safe way of representing claims to be transferred between two parties. JWT will be used to securely authenticate users, ensuring the platform verifies the identity of interviewers, candidates, and administrators.
OAuth2: A protocol that allows secure authorization in a simple and standardized way, enabling users to log in using their social or institutional accounts (Google, Facebook, etc.). It will provide secure access to the platform.
Passport.js: A flexible and modular authentication middleware for Node.js. It will integrate multiple authentication strategies (e.g., OAuth2, JWT) and streamline the login and registration process for users.

5. Payment Gateway:
Stripe: A payment processing platform that allows businesses to accept payments online. It will be used for handling donations, subscriptions, or any payment-related functionalities within the alumni or interview platform.
PayPal: Another widely used payment service, which can serve as an alternative payment method. PayPal will provide users with the ability to contribute to donations or make other payments securely.
```
## Dependencies
```
1. Frontend Development
Technologies: React.js, Redux, Bootstrap
Timeline: 30 days
Budget: Rs. 1,20,000

2. Backend Development
Technologies: Node.js, Express.js, GraphQL
Timeline: 30 days
Budget: Rs. 1,50,000

3. Database Setup
Technologies: MongoDB, PostgreSQL
Timeline: 15 days
Budget: Rs. 70,000

4. Authentication & Security
Technologies: JWT, OAuth2, Passport.js
Timeline: 15 days
Budget: Rs. 40,000

5. Payment Gateway Integration
Technologies: Stripe, PayPal
Timeline: 10 days
Budget: Rs. 50,000

6. Testing & Deployment
Timeline: 10 days
Budget: Rs. 70,000

Total Timeline: 30 Days
Total Budget: Rs. 5,00,000
```
