# API Token Risk Governor

Continuously rotate, scope, and validate high-risk API tokens.

## Priority Metadata

- ID: 113
- Domain: security-agent
- TTE (days): 5
- Exposure score: 7/10
- Wave: 2
- Priority score: 6.20

## Phase-1 Build

1. Risk/exposure assessment API.
2. Deterministic launch planning endpoint.
3. Domain-tailored threat and rollout docs.
4. CI test gate and local runnable service.
5. Spatial 3D starter (for spatial projects).

## Run

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -e .[dev]
make test
make run
```
