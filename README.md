# Hey, I'm Ayush Sharma

**Software Development Engineer II** at [Jupiter Money](https://www.jupiter.money/) · Distributed Systems · Fintech, Risk & Lending

I build backend systems for fraud detection, credit underwriting and BNPL lending, mostly in Java and Spring Boot. I own 12+ production services that process 1M events a day at 99.9% uptime.

## What I've delivered

- **Fraud detection:** integrated 6+ third-party fraud and risk signals into onboarding and pre-disbursal checks, blocking 30% of fraudulent users at onboarding
- **BNPL credit line:** built the BNPL credit line and credit limit engine from scratch and used it to take 3 lending partners live (SuperMoney, GoKwik and ShopSe), driving 30% revenue growth for lending
- **Approvals:** added a bank statement fallback when Account Aggregator consent fails, lifting approvals by 15%+
- **KYC cost:** replaced video KYC with liveness checks for smaller loans and moved traffic to cheaper CKYC, cutting KYC cost by ~25%
- **Underwriting:** shipped ~40 credit policy changes and new ML models for new and repeat customers, cutting false positives by 20% and default rates by 10%+
- **Risk guardrails:** built an automated exposure circuit breaker that has triggered 20+ times in production, plus live dashboards for 10+ risk models
- **Infra cost:** moved to Databricks and Redis Cloud and upgraded Java 17 to 21, cutting infrastructure cost by 30%
- **AI on-call agent:** connected Claude to Grafana, Slack, GitHub and Jira using MCP, cutting alert triage effort by 95%

## Tech Stack

**Languages:** Java, Python, Scala, Kotlin, SQL

**Backend & Architecture:** Spring Boot, Microservices, REST APIs, Event-Driven Architecture, Rules / Policy Engines

**AI & GenAI:** Model Context Protocol (MCP), Agentic AI Workflows, Prompt Engineering, AI-Assisted Coding (Claude)

**Data & Streaming:** Apache Kafka, Akka Streams, Apache Airflow, Databricks

**Databases:** PostgreSQL, DynamoDB, Redis, Elasticsearch, TimescaleDB

**Cloud & DevOps:** AWS (Lambda, EC2, DynamoDB), Docker, Kubernetes, Spinnaker, CI/CD

**Observability:** Prometheus, Grafana, Kibana

## Featured Projects

### [Movie Ticket Booking System](https://github.com/ayush26sharma/movie-ticket-booking)
Seat booking backend in Spring Boot 3 and PostgreSQL. It uses a conditional `UPDATE` instead of locks to handle concurrent bookings, and a 100-thread race test shows no seat is ever double-booked.

### [Metrics Publisher Service](https://github.com/ayush26sharma/metrics-publisher-service)
Distributed time-series metrics platform on a 4-stage Kafka pipeline, with Redis-based cardinality limits, T-Digest quantile estimates and a REST API for P95, SUM, AVG and RATE queries.

### [Flow-Controlled Inter-Process Communication](https://github.com/ayush26sharma/Inter-Process-Communication-flow-controlled)
Reliable Linux IPC in C over Unix domain sockets, FIFOs and message queues, comparing all three under the same acknowledgement-based flow control protocol.

### [Information Retrieval & Graph Ranking Algorithms](https://github.com/ayush26sharma/CSE508_Winter2023_28)
Inverted and positional indexes, TF-IDF and Naive Bayes classification, and PageRank and HITS, all built from scratch for IIIT Delhi coursework.

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ayush-sharma-2609/)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:sharma.as.ayush@gmail.com)

---

![Profile views](https://komarev.com/ghpvc/?username=ayush26sharma&style=flat-square)
