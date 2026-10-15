# Platform Reliability Lab

Platform Reliability Engineering and SRE knowledge repository.

---

## Reliability Lifecycle

```mermaid
flowchart TD

    A[Users]
    B[Services]
    C[Monitoring]
    D[SLIs]
    E[SLOs]
    F[Error Budgets]
    G[Incident Response]
    H[Postmortem]
    I[Continuous Improvement]

    A --> B
    B --> C
    C --> D
    D --> E
    E --> F
    F --> G
    G --> H
    H --> I
```

---

## Observability Model

```mermaid
flowchart TD

    A[Application]

    A --> B[Metrics]
    A --> C[Logs]
    A --> D[Traces]

    B --> E[Prometheus]
    C --> F[Log Platform]
    D --> G[Tracing Platform]

    E --> H[Grafana Dashboard]
    F --> H
    G --> H

    H --> I[Alerting]

    I --> J[Incident Response]
```

---

## Contents

### Reliability Foundations

- Service Level Indicators (SLIs)
- Service Level Objectives (SLOs)
- Error Budgets

### Incident Response

- Incident Management
- Postmortems

### Operational Readiness

- Production Readiness Reviews

---

## Focus Areas

- Site Reliability Engineering (SRE)
- Reliability Engineering
- Observability
- Monitoring and Alerting
- Incident Response
- Production Operations
- Service Reliability

---

## Navigation

| Topic | Link |
|--------|--------|
| Service Level Indicators | slis.md |
| Service Level Objectives | slos.md |
| Error Budgets | error-budgets.md |
| Incident Management | incident-management.md |
| Postmortems | postmortems.md |
| Production Readiness | production-readiness.md |
