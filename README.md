# DataPath AI: An AI Career Coach for Junior Data Analysts

## Project Overview

DataPath AI is an AI-powered career coaching assistant I created using Google NotebookLM as part of my AI Pre-Apprenticeship Capstone.

The assistant is designed to help aspiring data analysts, students, and career changers better understand entry-level job expectations, prepare for interviews, identify skill gaps, and develop realistic career plans.

Rather than relying only on general AI-generated advice, DataPath AI uses uploaded career resources to provide more relevant, source-grounded guidance.

## Problem and Goal

Breaking into data analytics can be overwhelming, especially when job descriptions list many different technical skills, qualifications, and experience requirements.

As a Data Analytics student, I wanted to explore how AI could help someone understand where they currently stand and what steps they could take to become a stronger candidate.

My goal was to create an assistant that could:

- Evaluate qualifications against entry-level data analyst expectations.
- Identify relevant skills and potential gaps.
- Generate realistic interview practice questions.
- Develop a measurable 30/60/90-day career development plan.
- Provide guidance supported by uploaded resources.

## Tools and Sources

**Primary Tool:** Google NotebookLM

**Assistant Name:** DataPath AI

I uploaded four resources into NotebookLM:

1. **Personal resume:** Used privately to evaluate existing education, experience, certifications, and technical skills.
2. **Junior Data Analyst Roles and Responsibilities:** Used to identify common responsibilities and qualifications associated with junior analyst positions.
3. **Data Analyst Career Guide:** Used to understand career pathways, technical skills, and professional development recommendations.
4. **Data Analyst Interview Preparation Guide:** Used to generate relevant technical and behavioral interview questions.

My personal resume was used only within NotebookLM and is not included in this public repository.

## How It Works

DataPath AI uses NotebookLM's source-grounded question-answering capabilities.

I uploaded career-related documents, configured the notebook to provide career guidance based on those resources, and tested the assistant with three prompts.

The three tests focused on career readiness, mock interview preparation, and career planning.

I then reviewed the outputs for usefulness, accuracy, personalization, and limitations.

## Examples and Screenshots

### Test 1: Career Guidance and Skill Gap Analysis

**Purpose:** Evaluate my readiness for an entry-level data analyst position using my resume, a junior analyst role guide, and a career resource.

I asked DataPath AI to identify my existing qualifications, potential skill gaps, and areas for improvement.

The initial response identified relevant technical skills, education, and experience. However, it did not consistently distinguish between skills I had used in practical settings and skills I had learned through coursework or certifications.

I revised my prompt to request that distinction explicitly.

The improved response provided a more nuanced assessment of my background and acknowledged some uncertainty.

**What I learned:** AI-generated career guidance becomes more useful when prompts specify how experience should be evaluated. Listing a skill on a resume does not necessarily demonstrate professional proficiency.

![Career guidance test](Screenshots/career%20guidance.png)

### Test 2: Mock Interview Preparation

**Purpose:** Generate realistic interview questions for an aspiring entry-level data analyst.

I asked DataPath AI to create five interview questions covering technical and behavioral topics, including SQL, Excel, data cleaning, and communication.

The assistant generated questions about SQL joins, Pivot Tables, handling missing data and outliers, communicating with nontechnical stakeholders, and learning new tools.

It also explained what interviewers might be assessing and what would make a strong response.

**What I learned:** DataPath AI was useful for identifying topics to practice and explaining the reasoning behind interview questions. However, because it provided answer guidance immediately, the experience was more like a study guide than a fully interactive mock interview.

![Mock interview test](Screenshots/mock%20interview.png)

### Test 3: 30/60/90-Day Career Action Plan

**Purpose:** Create a realistic career development plan for a Data Analytics student preparing for internships and future entry-level roles.

I asked DataPath AI to recommend specific goals, practical steps, and measurable outcomes while considering my coursework and other responsibilities.

The assistant generated three phases:

- **Days 1–30:** Strengthen SQL and spreadsheet skills.
- **Days 31–60:** Practice Python data cleaning and build a Tableau dashboard.
- **Days 61–90:** Review statistics, improve my resume, and apply for internships.

The response also suggested measurable deliverables, including SQL queries, a portfolio project, and an application tracker.

**What I learned:** The plan provided useful structure, but some recommendations were ambitious for the available time. I would need to adjust the workload and account for projects I had already completed or started.

![Career action plan test](Screenshots/career%20plan.png)

## Testing and Improvements

One important improvement I made was revising my career guidance prompt.

**Original prompt excerpt:**

"Using my uploaded resume, the junior data analyst job description, and the career guide, evaluate my readiness for an entry-level data analyst position."

The original prompt requested qualifications, skill gaps, priorities, and recommendations.

Although DataPath AI provided a useful assessment, it sometimes treated technical skills listed on my resume as evidence of practical proficiency.

**Improved prompt excerpt:**

"Could you separate the skills I've actually used in my work or projects from the ones I've only learned through courses or certifications? I don't want to overestimate my experience, but I also don't want to overlook what I've already accomplished."

I also instructed the assistant not to assume I lacked a skill simply because it was absent from my resume, and to distinguish required qualifications from preferred ones.

**Result:** The revised response was more specific about the difference between practical experience and foundational knowledge. It also acknowledged limitations in what could be determined from the uploaded sources.

This demonstrated how prompt refinement can improve the quality and usefulness of AI-generated career guidance.

## Responsible AI

I considered several responsible AI principles while building and testing DataPath AI.

**Privacy:** I used my resume within NotebookLM for testing but did not upload it to this public GitHub repository. Screenshots should exclude private contact details and other sensitive information.

**Accuracy:** AI-generated assessments may overstate proficiency or misinterpret job qualifications. I reviewed the outputs instead of assuming they were entirely correct.

**Transparency:** DataPath AI is a career guidance tool, not a professional recruiter or hiring decision-maker. Its recommendations depend on the uploaded sources and the information provided.

**Human Oversight:** I identified limitations in the generated responses, including potentially unrealistic timelines, generalized job requirements, and assumptions based on incomplete information.

**Fairness:** The assistant should avoid treating a nontraditional career path, an incomplete degree, or limited professional experience as proof that someone cannot succeed in data analytics.

AI can support career exploration, but users should verify important information and make their own career decisions.

## Career Action Plan

Based on DataPath AI's recommendations, I developed the following summary:

| Timeline | Focus | Measurable Outcome |
|---|---|---|
| Days 1–30 | SQL and spreadsheet fundamentals | Complete documented SQL queries and an Excel analysis |
| Days 31–60 | Python, Pandas, and visualization | Publish an analytics portfolio project |
| Days 61–90 | Statistics, interview preparation, and applications | Update resume and track 10–15 internship applications |

I would adapt these goals to my coursework, existing projects, and available time rather than treating the AI-generated schedule as a strict requirement.

## Reflection

This project helped me better understand how AI can support career development, particularly for students who are still building their technical skills and professional experience.

I found NotebookLM useful because it could work with career resources I selected rather than relying entirely on general responses.

The career guidance test was especially valuable because it demonstrated the importance of prompt engineering. When I revised my prompt to distinguish between practical experience and skills learned through coursework, the output became more relevant to my situation.

I also learned that a well-organized AI response is not necessarily a fully accurate or realistic one. For example, the career plan contained useful recommendations, but I still needed to evaluate whether the workload was achievable.

If I continued developing DataPath AI, I would improve the interview preparation experience by making it more interactive and allowing users to answer questions before receiving feedback.

Overall, this capstone reinforced the importance of using AI as a supportive tool while maintaining human judgment, verifying information, and protecting personal data.
