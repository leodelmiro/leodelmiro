## Leonardo Delmiro

Senior Backend Engineer at [Zup Innovation](https://www.zup.com.br/) (Itaú Unibanco group), based in Curitiba, Brazil.

I design and run distributed backend systems for high-scale financial platforms — Brazilian instant payments (PIX) and the migration of wire transfers (TED) from mainframe to AWS. Most of my work is about reliability: timeouts, retries, concurrency, and the observability you need to find out why something broke.

**Stack:** Kotlin · Java · Spring Boot · Micronaut · AWS (Lambda, SQS, SNS, EventBridge, S3) · Kafka · DynamoDB · Terraform · Datadog

**Lately:** spec-driven development with AI agents. My side projects below were planned with [OpenSpec](https://github.com/Fission-AI/OpenSpec) before any code was written.

### Side projects

- **[LibrasAnki](https://github.com/leodelmiro/LibrasAnki)** — builds Anki decks for Brazilian Sign Language (LIBRAS) from the official INES dictionary, with the sign's video embedded in every card. Handles the dictionary's gaps and data errors explicitly instead of hiding them.
- **[imdb-to-letterboxd](https://github.com/leodelmiro/imdb-to-letterboxd)** — migrates your IMDb *Watch History* to Letterboxd. IMDb has no export for it; this fills exactly that gap, with a reconciliation report as the acceptance test.

### Architecture studies

- **FIAP Software Architecture** — microservices on Kubernetes with Terraform, API Gateway and a Lambda authorizer ([infra](https://github.com/leodelmiro/tech-challenge-estabelecimento-infra), [orders](https://github.com/leodelmiro/tech-challenge-estabelecimento-pedido), [payments](https://github.com/leodelmiro/tech-challenge-estabelecimento-pagamento)), and an event-driven video processing pipeline ([processing](https://github.com/leodelmiro/fiap-hackaton-video-processa), [infra](https://github.com/leodelmiro/fiap-hackaton-video-infra)).
- **[Lock](https://github.com/leodelmiro/Lock)** — optimistic vs. pessimistic locking in Java.

### Certifications

AWS Certified Developer – Associate · AWS Certified AI Practitioner

[LinkedIn](https://www.linkedin.com/in/leodelmiro/)
