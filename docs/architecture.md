# Architecture

High-level overview of the engineering-hackathon project.

## Components

| Directory | Responsibility |
| --- | --- |
| `frontend/` | User-facing application |
| `backend/` | API and business logic |
| `agent/` | Autonomous / LLM agent services |
| `messaging/` | Event and message handling |
| `tests/` | Cross-cutting and integration tests |

## System diagram

```text
frontend  -->  backend  -->  agent
                 |            |
                 +--> messaging <--+
```

Add service contracts, data flow, and deployment notes here as the project grows.
