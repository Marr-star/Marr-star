# AI-Powered Skill Mentor for Job Seekers & Recruiters

**Full-stack AI career guidance platform | Team graduation project**

## Project Overview

**AI-Powered Skill Mentor for Job Seekers & Recruiters** is a team-developed, full-stack AI career guidance and talent-matching platform designed to bridge the gap between candidates' capabilities and the skills employers need.

For **job seekers**, the platform analyzes resumes, identifies existing skills and skill gaps, estimates readiness for target job roles, and recommends personalized courses and career development roadmaps. It incorporates live labor-market information to help candidates understand evolving job requirements and make informed career decisions.

For **recruiters**, the platform provides AI-assisted insight into the alignment between candidate skills and job-role requirements, making candidate evaluation and skill-based matching more explainable. Its hybrid matching approach supports both predefined and previously unseen job roles.

The platform combines knowledge-based matching, Retrieval-Augmented Generation (RAG), semantic embeddings, and labor-market data to support more informed decisions on **both sides of the hiring process**.

> **Repository note:** This is a description of my contributions to a collaborative graduation project. The original project repository is private, so the full source code is not publicly available here.

## My Role & Contributions

I worked as part of the development team, with a primary focus on the AI-driven skill-gap and recommendation capabilities.

- **Designed a hybrid Skill Gap Analysis Engine** that combines knowledge-based job-role matching (approximately **15 ms** for the knowledge-based matching path, as measured during the project) with a Retrieval-Augmented Generation (RAG) pipeline, allowing the system to handle both predefined and previously unseen job roles.
- **Integrated live job-market information through the Adzuna API** to make role and skill recommendations more relevant to current opportunities.
- **Used FAISS, Chroma, and semantic embeddings** to support retrieval, matching, and explainable, personalized career recommendations.
- **Worked with Groq and the `all-MiniLM-L6-v2` embedding model** as part of the AI pipeline, with a focus on connecting candidate skills to job requirements and generating actionable learning roadmaps.
- **Collaborated with the team to improve the accuracy and relevance of outputs from the course recommendation microservice**, helping refine the quality of recommended learning resources.
- **Currently contributing to deployment** of the application. Deployment is in progress; a public live demo is not yet available.

## Technologies Used

`Python` · `RAG` · `Groq` · `FAISS` · `Chroma` · `Sentence Transformers (all-MiniLM-L6-v2)` · `Adzuna API` · `Semantic Search` · `Explainable AI`

## Key Features of the Team Project

**For job seekers**
- Resume analysis and skill extraction
- Job-role matching and readiness scoring
- Skill-gap identification for target roles
- Personalized course recommendations and career roadmaps
- Live labor-market information to inform career planning

**For recruiters**
- Candidate skill-to-role alignment insights
- Explainable, skill-based evaluation relative to role requirements
- Matching support for both predefined and previously unseen job roles

**Underlying AI capabilities**
- Hybrid knowledge-based role matching and RAG
- Semantic search using FAISS, Chroma, and embeddings

## Project Status

**Team project completed for graduation; deployment work is ongoing.**

## Collaboration & Attribution

This project was developed collaboratively. The features listed under **My Role & Contributions** describe my individual technical involvement; the wider platform and its other components were built with the team.


