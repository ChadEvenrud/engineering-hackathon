# Engineering Hackathon

Monorepo scaffold for the frontend, backend, agent, and messaging services.

## Layout

```text
engineering-hackathon/
├── frontend/
├── backend/
├── agent/
├── messaging/
├── tests/
├── docs/
│   └── architecture.md
├── .github/
│   └── workflows/
│       ├── pull-request.yml
│       └── build.yml
├── docker-compose.yml
└── README.md
```

## Getting started

1. Add service code under `frontend/`, `backend/`, `agent/`, and `messaging/`.
2. Put shared tests in `tests/`.
3. Update `docs/architecture.md` as the design lands.
4. Run the stack with `docker compose up` once each service has a Dockerfile.
