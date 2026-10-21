# TestBudget Demo Fixture

This is a small deterministic repository used to demonstrate TestBudget.

The repository intentionally contains a tiny pytest suite so TestBudget's
planning, audit-mode execution, and result ingestion can be demonstrated
quickly and reliably.

## Test suite

The fixture contains three tests:

- addition
- subtraction
- multiplication

Run locally with:

```bash
python -m pip install -e ".[dev]"
python -m pytest -q