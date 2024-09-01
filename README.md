# Unlocking Knowledge and Empowering Students with AI (Chat Scholar)

## Problem Statement:
In today's digital age, students are inundated with information from textbooks, research papers, and online resources. Navigating this vast sea of knowledge and extracting meaningful insights can be overwhelming. Chat Scholar addresses this challenge by providing an AI-powered platform that simplifies academic learning and enhances the writing process.
Context:
Leveraging the power of machine learning, natural language & Gen AI, this tool automates the traditionally manual insurance claim processing procedure. 
•	Implementation of AI and Generative AI will enhance data analysis and   predictive capabilities.
•	AI will provide deeper insights, improve accuracy, and streamline reporting processes.
•	Predictive features will enable proactive decision-making based on anticipated impact fluctuations.

## Objective:
Chat Scholar has two primary objectives.
1.	Academic Research and Understanding: Chat Scholar provides clear and concise answers, summaries, and explanations tailored to the student's specific questions and the content of their documents.
2.	Essay Grading Rubric: Teachers and instructors can create and upload their own custom rubrics to personalize essay evaluation and ensure alignment with specific course requirements.
How it works:
1.	Document Upload and Processing: Users upload PDF documents, and the application extracts the textual content.
2.	Text Embedding and Semantic Search: The extracted text is processed, embeddings are generated, and a semantic search engine (using FAISS) allows for efficient retrieval of relevant information.
3.	Question Answering: Students' questions are processed, compared to the indexed content, and the most relevant information is used to generate a comprehensive answer using the OpenAI LLM.
4.	Essay Grading Rubric:
•	Rubric Selection: Students can choose from pre-defined rubrics (e.g., IELTS, TOEFL) or upload custom rubrics created by their teachers.
•	Essay Evaluation: The rubric tool analyses the student's essay against the selected rubric's criteria.
•	Feedback Generation: Based on the analysis, Chat Scholar provides feedback on the essay's strengths and areas for improvement, highlighting specific criteria met or not met.
Key Inputs: 
For this particular project, we would need the below key inputs:
•	Chat Scholar
o	Upload the document (pdf) for which you want chat bot.
•	Essay Grading Rubric
o	Choose the pre-defined rubric (IELTS/TOEFL) or upload the custom rubric.
o	The rubric tool analyses the student's essay against the selected rubric's criteria.

## Architecture:

![image](https://github.com/user-attachments/assets/2d9220ce-9573-4a09-9aa5-85d26747750e)

- **Step 1: Data Collection:**
Once the document is uploaded it initiates chat scholar which automatically convert the extract the data from the document and convert the data into small chunks size. 
- **Step 2: Embeddings Generation**
In this stage, textual data is converted into numerical embeddings using advanced techniques. These embeddings capture the semantic relationships within the data, enabling to retrieve and analyze information efficiently
- **Step 3: Query Execution **
Once the processing is done, Chat Scholar uses OpenAI Large Language Model (LLM) to generate the response. Both context and query is passed to the LLM to generate the best possible response.

## Product Demo:

![image](https://github.com/user-attachments/assets/00381e40-4305-4cf5-afad-3a6881d6b262)

![image](https://github.com/user-attachments/assets/05f9aa99-447e-444e-9e9e-45455eafda61)

## Product Report:
Chat Scholar represents a significant step towards leveraging AI to create a more engaging and effective learning experience for students, empowering them to excel in their academic pursuits.




