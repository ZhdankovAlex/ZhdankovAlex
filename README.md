# Hi, I'm Alex 👋

Senior Backend Engineer with 6 years of Python and PostgreSQL, building distributed systems
for banking and enterprise software. Based in Novi Sad, Serbia (CET).

### What I've built

- **Control-plane / agent platform for PostgreSQL** at Diasoft: deployment time cut from 2 hours to 10 minutes
- **RAG assistant retrieval layer** with measured quality: hit@1 raised from 46% to 79%
- **Dashboard performance**: load time from 2 s to 300 ms by removing N+1 queries and moving aggregation into PostgreSQL
- **Durable metrics buffer** (SQLite, at-least-once delivery) that survives 33 days of control-plane outage
- **Real-time psql terminal in the browser** (WebSocket, Redis Streams): incident investigation from ~1 hour to 15 minutes
- **Zero-downtime INT32 → INT64 primary key migration** on a multi-terabyte production database

### Side project

**[job-hunter](https://github.com/ZhdankovAlex/job-hunter)**: a self-hosted job search assistant.
It collects vacancies from ATS boards and aggregators, filters them by the full text, ranks them
against my CV, tracks applications from Gmail (read-only) and builds a tailored CV and cover letter
for any vacancy. Python, FastAPI, SSE, a ~10-source async-free crawler with robots.txt and rate limits.

### Stack

Python · FastAPI · PostgreSQL · Redis · SQLite · Docker · Kubernetes · WebSocket · RAG / embeddings · Claude Code

### Elsewhere

[LinkedIn](https://linkedin.com/in/alex-zhdankov) · [dev.to](https://dev.to/alex_zhdankov) · [Telegram](https://t.me/Zhdankov_Alex)
