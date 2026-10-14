# Error Budgets

## Definition

Error budgets allow controlled failure within a service.

### Example

```text
SLO = 99.9%

Allowed Downtime Monthly:

43.8 minutes
```

---

## Error Budget Flow

```mermaid
flowchart TD

    A[SLO 99.9 Percent]

    A --> B[Monthly Error Budget]

    B --> C{Budget Remaining?}

    C -->|Yes| D[Continue Releases]

    C -->|No| E[Pause Releases]

    E --> F[Improve Reliability]
```

---

## Usage

Error budgets guide:

- Release decisions
- Risk management
- Operational priorities

---

## When Budget Is Exhausted

- Pause releases
- Reduce operational risk
- Improve reliability

---

## Navigation

| Previous | Home | Next |
|-----------|------|------|
| slos.md | index.md | incident-management.md |
