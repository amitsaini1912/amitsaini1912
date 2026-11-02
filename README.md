### Hi, I'm Amit 👋

Final-year CSE student at UIET Panjab University (2027). I build backend systems that move money — and prove
they're correct with tests, load tests and chaos tests.

**Looking for:** a 6-month software engineering internship from **January 2027** (backend / fintech) and 2027
new-grad roles.

### Featured projects

**[Hospital Payments Platform](https://github.com/amitsaini1912/patient-management-microservices)** — Java 21, Spring Boot, Kafka, PostgreSQL, Redis, gRPC
- Double-entry ledger enforced by Postgres, idempotent money-moving APIs, PCI-style card vault, ISO 8583-style card network simulator, reconciliation, audit chain
- 120 concurrent refunds → acquirer called exactly once per step · k6: 8,324 checkouts, 0 errors, p95 93 ms
- Chaos-tested: Kafka down 60 s → 0 failed payments, 936 outbox events delivered within 5 s of recovery

**[Payment Risk Engine](https://github.com/amitsaini1912/payment-risk-engine)** — Python, FastAPI, Redis, scikit-learn
- Real-time allow / hold / block inside a 300 ms budget, with reason codes
- Cost-tuned model: recall 0.81, −86% expected loss vs approving everything (synthetic data)
- Chargebacks flow back via Kafka as training labels; shadow model + drift monitoring

**813 automated tests** across both · ~92% line coverage on the payment services · CI on GitHub Actions

### Stack
Java · Spring Boot · Kafka · PostgreSQL · Redis · gRPC · Docker · Kubernetes · Python · FastAPI · scikit-learn · MERN

### Also
600+ DSA problems in Java ([LeetCode](https://leetcode.com/u/amitkumarsainig9/) 1573) · HackerRank SQL (Intermediate)

📫 amitkumarsainig9@gmail.com · [LinkedIn](https://www.linkedin.com/in/amitsaini1912/)
