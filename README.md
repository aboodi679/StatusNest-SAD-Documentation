# StatusNest — Solution Architecture Document

Solution Architecture Document (SAD) for **StatusNest**, a cloud-native, multi-tenant SaaS platform for monitoring web services and publishing real-time public status pages — built entirely on AWS.

## Contents

| File | Description |
|---|---|
| `StatusNest-SAD.md` | Markdown source of the SAD |
| `StatusNest-SAD.pdf` | Final formatted PDF (with architecture diagrams) |

## Stack

AWS (ECS Fargate, RDS PostgreSQL, ElastiCache Redis, Lambda, SQS, CloudFront, WAF) · Terraform · GitHub Actions (OIDC)

## Related Repositories

| Repo | Purpose |
|---|---|
| [statusnest-frontend](https://github.com/aboodi679/statusnest-frontend) | React SPA |
| [statusnest-api](https://github.com/aboodi679/statusnest-api) | FastAPI microservices |
| [statusnest-worker](https://github.com/aboodi679/statusnest-worker) | Lambda monitoring engine |
| [statusnest-infra](https://github.com/aboodi679/statusnest-infra) | Terraform IaC |

**Author:** Muhammad Abdullah — [github.com/aboodi679](https://github.com/aboodi679)
