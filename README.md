## Hi, I'm Paolo 👋

Backend engineer. I work on **distributed systems in Java**: large-scale
enterprise platforms where sessions, messaging and transactions have to stay
correct across service boundaries.

Most of my work lives in private repositories, so this profile is where I
publish what I can share: the demos behind the things I write.

### Writing

I write about problems I have hit in production and the design decisions
behind them, with a reproducible repo attached.

- **[Your Search Query Is a Program: Composing Role-Based SQL With the Strategy Pattern](https://dev.to/purbano/your-search-query-is-a-program-composing-role-based-sql-with-the-strategy-pattern-3o3a)**.
  Why a search with optional filters and role-based visibility is application
  logic, not a string, and how to compose it from strategies with a builder
  that makes the AND/OR precedence leak impossible.
  Repo: [`search-query-composition-demo`](https://github.com/PaoloUrbano/search-query-composition-demo)

- **[The Row Says 'system': Spring Data JPA Auditing Outside the HTTP Request](https://dev.to/purbano/the-row-says-system-spring-data-jpa-auditing-outside-the-http-request-f77)**.
  Where the auditor's identity comes from when the write does not start from an
  HTTP request: scheduled jobs, queue consumers, and the fallback that stops
  half your rows from saying `system`.
  Repo: [`auditor-aware-demo`](https://github.com/PaoloUrbano/auditor-aware-demo)

- **[Where OpenTelemetry Stops: The Missing 44ms in a Spring Boot Trace](https://dev.to/purbano/where-opentelemetry-stops-the-missing-44ms-in-a-spring-boot-trace-ld9)**.
  Distributed tracing across two Spring Boot services, and what
  auto-instrumentation cannot see.
  Repo: [`spring-boot-otel-demo`](https://github.com/PaoloUrbano/spring-boot-otel-demo)

More articles, including shorter explainers without a repo, on [dev.to/purbano](https://dev.to/purbano).
