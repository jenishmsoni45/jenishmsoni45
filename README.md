# Jenish Soni

Computer Science co-op student at Toronto Metropolitan University, graduating August 2028.
I build backend systems, and I care most about what happens when things go wrong:
retries, duplicates, crashes and overload.

I'm a software engineer intern on the Enterprise AI team at Foresters Financial.
Before that I interned at TD Bank and Compugen.

## Projects

- **job-queue** (Go, Postgres): a multi-tenant durable job queue. When one tenant sends
  100x its normal traffic, the others' p99 wait stays under 400 ms instead of 162 s under FIFO.
- **tally** (Java, Spring Boot, Kafka): a double-entry ledger where a retried request moves
  money once. 1,800 transfers/s at p99 under 50 ms, tested through database cuts, a Kafka
  outage and `kill -9`.
- **vaultline** (Rust): a CLI that injects secrets from an encrypted vault into a process
  at run time, with a written threat model and 45 CPU-hours of fuzzing.
- **risk-engine** (Python, Redis, Kafka): an allow/hold/block decision engine over a
  ledger's event stream. p99 of 6 ms at 800 decisions/s.

## Up next

- **eval-harness** (Python, Inspect): an evaluation harness for coding agents, with sandboxed
  tasks, hidden-test grading and checks for agents that edit tests instead of fixing the bug.
  In design; build starts after the job queue's ops console.

## Tools

Java, Python, Go, Rust, SQL · PostgreSQL, Kafka, Redis · Docker, Kubernetes, Terraform, GitHub Actions

## Contact

[LinkedIn](https://www.linkedin.com/in/jenishsoni/) · [jenishsoni.com](https://jenishsoni.com)
