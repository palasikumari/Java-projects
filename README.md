Overview

A system where recruiters upload job descriptions and candidates upload resumes. The app uses NLP to evaluate how well each resume matches the job description and ranks them accordingly.

Backend (Java + Spring Boot)
REST APIs for resume/job upload, scoring, and ranking

Integration with Python-based ML service

Spring Security (optional for login/roles)

File handling (Apache POI or PDFBox for parsing)


🔹 ML/NLP Engine (Python microservice)

Flask or FastAPI for REST API

NLP with spaCy or transformers (e.g., BERT)

Cosine similarity / embeddings to score relevance


🔹 Database

PostgreSQL or MongoDB (to store resume metadata and scores)

ai-resume-ranker/
├── backend-java/
│   ├── src/main/java/com/ranker/
│   │   ├── controller/
│   │   ├── service/
│   │   ├── model/
│   │   └── config/
│   └── resources/
│       └── application.yml
├── ml-nlp-engine/
│   ├── app.py
│   ├── model_utils.py
│   └── requirements.txt
└── README.md
