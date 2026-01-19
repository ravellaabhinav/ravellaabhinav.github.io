---
title: "Citi Bank"
date: 2025-07-01
params:
  company: "Citi Bank"
  role: "Software Engineer"
  location: "New York, USA"
  start: "Jul 2025"
  end: "Present"
  logo: "img/logos/citi.svg"
  tags: ["Java", "Spring Boot", "Kafka", "AWS", "Kubernetes", "Observability"]
---

- Developed **17 Spring Boot REST microservices** for payment execution, account-state processing, and orchestration, processing **500K+ daily events** while maintaining **p95 latency < 180ms**.
- Re-architected monolithic Java applications into independent microservices, reducing release coupling by **60%**, cutting change lead time from **5 days → 2 days**, and lowering recurring incidents by **25%**.
- Engineered **Kafka event pipelines** with idempotent consumers + full-tolerant retries, preventing duplicate postings and reducing reconciliation breaks by **35%**.
- Optimized AWS infrastructure (**EC2, RDS, Auto Scaling**) with workload-aware autoscaling and capacity planning, reducing monthly spend by **22%** without breaching latency SLOs.
- Implemented IAM, **RBAC**, OAuth2, and JWT-based security for financial endpoints; passed quarterly audits with **zero critical findings**.
- Built production observability with **Prometheus, Grafana, tracing, centralized logging**, reducing incident detection time **45 min → 5 min**, lowering MTTR by **32%**.
- Automated CI/CD with GitHub Actions, Jenkins, Docker, and Kubernetes, increasing deployment frequency from weekly to **3× per week** and reducing rollback rates by **40%**.
