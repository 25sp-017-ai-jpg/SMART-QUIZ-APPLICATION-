# SMART-QUIZ-APPLICATION-
An Interactive Online Quiz Platform 
## UIT University  
### Department of Computer Science / Artificial Intelligence Fall 2025, Semester II 
<!DOCTYPE html>
<html>
<head>
</head>
<body>
     <div style="background-color:black;color:white;padding:20px;"> 
          <h2> Group Members </h2>
          <table style="width:100%">
  <tr>
    <th>Student Id</th>
    <th>Student Name</th> 
  </tr>
  <tr>
       <td>25SP-017-AI</td>
       <td>Abdullah Usman</td>
  </tr>
  <tr>
    <td>25SP-020-AI</td>
    <td>Muhammad Suffiyan Affandi</td>
  </tr>
  <tr>
    <td>25SP-002-AI</td>
    <td>Bilal Jalil</td>
  </tr>
  </tr>
</table>
          
## 📑 Table of Contents

## 📑 Table of Contents

1. ABSTRACT
2. INTRODUCTION
   - Project Overview
   - Need for the System
   - Scope of the Project 
3. Objectives
4. PROBLEM STATEMENT 
5. SYSTEM REQUIREMENTS
   - Functional Requirements
   - Non-Functional Requirements
   - Hardware Requirements
   - Software Requirements 
6. METHODOLOGY
   - System Architecture
   - Technology Stack
   - Development Methodology
   - Implementation Details 
7. SYSTEM DESIGN
   - Class Diagram
   - Database Design
   - System Flow
8. IMPLEMENTATION
   - Backend Implementation
   - Frontend Implementation
   - Database Implementation
9. RESULTS AND DISCUSSION
   - Features Implemented
   - Screenshots
   - Testing Results
10. CONCLUSION AND FUTURE WORK
11. REFERENCES
12. APPENDIX

### Abstract
The Smart Quiz Application is a comprehensive web-based platform developed 
using Spring Boot framework that provides an interactive environment for 
conducting online quizzes. The system enables users to take timed quizzes on 
various topics, receive instant feedback, and review their performance with 
detailed explanations. The application features a responsive frontend built with 
HTML, CSS, and JavaScript that communicates with a robust backend powered 
by Spring Boot and H2 database. Key functionalities include quiz management, 
automatic scoring, time tracking, result analysis, and question review. The 
system follows MVC architecture and implements RESTful APIs for seamless 
communication between frontend and backend components. This project 
demonstrates the practical application of modern web development 
technologies in creating an educational tool that enhances learning through 
interactive assessment. 

## Introduction: 
### Project Overview 
In the digital era of education, online assessment systems have become 
essential tools for evaluating knowledge and skills. The Smart Quiz Application 
is designed to address the growing need for interactive, reliable, and user
friendly online testing platforms. This system allows administrators to create 
and manage quizzes while providing users with an engaging testing experience. 
### Need for the System: 
Traditional paper-based quizzes suffer from limitations such as manual grading, 
delayed results, and lack of interactive feedback. Educational institutions and 
corporate training programs require automated systems that can: 
• Provide instant evaluation and results 
• Offer detailed feedback and explanations 
• Track user progress over time 
• Support various question types 
• Ensure fair timing and monitoring 
### Scope of the Project 
The Smart Quiz Application covers the following scope: 
• User registration and authentication (basic implementation) 
• Quiz creation and management 
• Multiple-choice question support 
• Real-time timer and progress tracking 
• Automatic scoring and result generation 
• Detailed performance analysis 
• Responsive web interface 
## Objectives: 
The primary objectives of this project are: 
1. To develop a user-friendly online quiz platform using Spring Boot 
2. To implement RESTful APIs for seamless frontend-backend communication 
3. To create a responsive and intuitive user interface 
4. To ensure accurate and automatic scoring system 
5. To provide detailed feedback with explanations 
6. To implement time management features for quizzes 
7. To develop a scalable and maintainable codebase 
8. To integrate an in-memory database for rapid development.
## Problem Statement: 
The traditional methods of conducting quizzes and assessments face several challenges: 
1. Manual Evaluation: Paper-based quizzes require extensive time for grading and result calculation 
2. Delayed Feedback: Students receive results days or weeks after taking tests 
3. Limited Analytics: Lack of detailed performance analysis and progress tracking 
4. Time Management: Difficulty in enforcing strict time limits manually 
5. Accessibility Issues: Physical presence required for traditional tests 
6. Resource Intensive: High costs for printing, distribution, and manual evaluation 
7. No Immediate Feedback: Students cannot learn from mistakes immediately
8. The Smart Quiz Application addresses these issues by providing an automated, interactive, and efficient online assessment platform.
## Methodology: 
### System Architecture 
The application follows a three-tier architecture: 
1. Presentation Layer: HTML, CSS, JavaScript frontend 
2. Application Layer: Spring Boot REST API 
3. Data Layer: H2 Database with JPA 
### Technology Stack 
1.  Backend: Spring Boot 3.5.9, Java 17
2.  Frontend: HTML5, CSS3, JavaScript (ES6)
3.  Database: H2 In-memory Database
4.  ORM: Spring Data JPA
5.  Build Tool: Maven
6.  IDE: IntelliJ IDEA / VS Code 
### Development Methodology 
The project follows an Agile development approach with iterative sprints: 
1. Requirement Analysis 
2. System Design 
3. Backend Development 
4. Frontend Development 
5. Integration Testing 
6. Deployment 
6.4 Implementation Details 
