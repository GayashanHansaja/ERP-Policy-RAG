# ERP-Policy-RAG

This repository contains a policy-aware RAG service for ERP employee registration validation.

## Project structure

- `rag-system/` — main application code, API routes, validation logic, scripts, and tests.
- `rag-system/fixtures/employee_registration_policies_sri_lanka/` — synthetic policy corpus used by the registration gate.
- `rag-system/docs/` — API usage and evaluation methodology.

## Quick start

1. Open the service workspace:
   - `cd rag-system`
2. Review setup and runtime instructions in:
   - `rag-system/README.md`

## What this system does

- Validates employee registration requests against policy documents.
- Returns decision outcomes (`ALLOW`, `BLOCK`, `ESCALATE`) for the ERP backend.
- Provides retrieval-backed policy context for validation decisions.
