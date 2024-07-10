---
title: "STAR Method"
date: 2024-05-31
draft: false
description: "a description"
tags: ["example", "tag"]
summary: "A summary of the Amazon STAR interview method as well as example applications using my own experiences."
---

# What is the STAR method?

The STAR method is a structured way of responding to behavioral interview questions by discussing the specific Situation, Task, Action, and Result of the situation you are describing.

# This is why it's important

The STAR method is important because it helps you provide clear and concise answers to interview questions. It ensures that you cover all necessary aspects of your experience, demonstrating your skills and abilities in a structured manner. This approach makes it easier for interviewers to understand the context of your achievements and assess your qualifications.


# Here are some STAR responses to common interview questions 

### 1. Can you describe a challenging technical problem you have solved?

**Situation:** During my tenure at Markel Group, I was tasked with simplifying the JSON schema of over 10 years of historic transaction data stored in our noSQL database. This was over 4.4 million historical policies that the business wanted to translate into a relational schema that could be used to run business reports on. Before this microservice, the current process involved an over 3 month wait to see the policy data at the end of the pipeline. 

**Task:** The primary challenge was to flatten this extensive JSON schema, originally containing 2,000 fields, into a more manageable format without losing crucial information.  

**Action:** I wrote the mapping logic for a C# microservice designed to convert the JSON schema into a simplified 200-field schema. This involved understanding the existing complex structure, identifying essential fields, and creating efficient mapping rules. I followed a waterfall based development approach. Using an excel sheet to highlight the needed fields, and my knowledge of the applications JSON schema from past projects. I wrote the logic to both map the JSON schema from non-simplified to simplified, as well as the unit test to verify this logic was correct.

**Result:** The new simplified schema greatly improved data accessibility and usability for business analytics and operations, facilitating better decision-making processes. The streamlined data also enhanced system performance and reduced processing times. 

### 2. Can you explain a project you have worked on, including your specific contributions and the technologies used?

**Situation:** As part of my senior capstone project at Virginia Commonwealth University, I worked on the Little Ram Pantries Web Dashboard, an initiative to combat food insecurity on campus.

**Task:** The project aimed to create a web dashboard that would interact with Raspberry Pis and webcams installed in newspaper stand boxes stocked with food, placed in busy campus buildings. The dashboard needed to monitor and manage food inventory to ensure consistent access for students.

**Action:** I developed the web dashboard using React and AWS Lambda functions written in Go. We transitioned to a serverless architecture after receiving feedback from a grant we received. I was responsible for creating this architecture, integrating the Raspberry Pis and webcams with the dashboard, designing and creating the MVP React web dashboard, and writing the Go microservices that process new images. Additionally, I went beyond the requirements of the project and included AI analysis to the image uploading pipeline. This allows the researching using the data to have a better understanding of the pantry usage. 

**Result:** The web dashboard successfully provided continuous food access to over 14,000 students in 2023. The project was recognized for its innovation and social impact, earning a Sternheimer grant and a third-place award for multidisciplinary engineering projects. This solution not only addressed a critical need on campus but also showcased the potential of technology-driven social initiatives.


### 3. How do you approach debugging and troubleshooting code?

**Situation:** As a part-time Associate Software Engineer at Markel Group, I worked on an external-facing web app that required frequent updates and bug fixes due to dynamic business needs.

**Task:** One notable task involved guiding an offshore development team to ensure a smooth upgrade from Angular 11 to Angular 15, which required comprehensive test coverage.

**Action:** With the guidance of the lead QA engineer, i helped introduce the team to Functionize, an automated testing tool that uses machine learning to streamline unit test maintenance. I collaborated with the offshore team to develop automated tests, achieving 100% test coverage. This proactive approach included detailed logging and monitoring to quickly identify and address issues.

**Result:** The upgrade to Angular 15 was frictionless, with no major disruptions reported. The automated tests significantly reduced maintenance time, allowing the team to focus on new feature development and improving overall product stability. The testing tool proved to be successful and the QA team continues to create new test with it. 

# When to not use STAR 

While the STAR method is highly effective for answering behavioral interview questions, it is not suitable for all types of questions. Avoid using STAR for questions that require straightforward, factual answers, such as questions about your technical skills or knowledge. It is also not necessary for questions that seek your opinions, hypothetical scenarios, or discussions about your career aspirations. Use STAR specifically for questions that ask you to describe past experiences and how you handled specific situations.