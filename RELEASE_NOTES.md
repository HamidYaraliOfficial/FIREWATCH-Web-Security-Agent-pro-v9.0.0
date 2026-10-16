# FIREWATCH Web Security Agent v9 Pro — Standards & Assurance Release

This release expands v9.0.0 into an auditable Standards & Assurance workspace alongside the web/API security testing platform.

## Standards checklist

- Curated register of **67 selected standards/framework references**, mapped across **32 domains** to **469 paraphrased control objectives**.
- Three relationship classes plus a direct/supporting/conditional/adjacent relationship taxonomy to distinguish core web/API testing from governance, applicability-dependent and neighboring requirements.
- Each control includes an identifier, requirement objective, acceptance criteria, evidence expectation, verification mode, priority, applicability, mapped framework IDs, relationship type and official source URL(s).
- Generated human-readable Markdown, JSON source of truth, CSV exports and a formatted Excel workbook with Dashboard, Master Checklist, Standards Register, Domain Summary and Methodology.
- Dashboard/API workflow for filters, status tracking, owner, reviewer, due date, evidence URL/note, exception justification, optimistic revision checks and audit history.
- CSV formula-injection safeguards, evidence URL validation and API-key gate integration.
- API filters include framework, domain, priority, applicability, status, verification mode, relationship type and search.
- Catalogue generator and CI drift check ensure generated files stay aligned with their source definitions.

## Verification

- **5,912 / 5,912 test cases passed**, across **58 test modules** in the final local regression run; zero failures/errors/skips reported.
- **86.67% combined Python statement coverage**, using eight deterministic shards with identical collection fingerprint and zero shard failures; minimum gate 80%.
- **67 standards/framework references, 469 checklist controls, 32 domains**. Every registered reference is mapped to at least one control.
- The demo report bundle's integrity manifest, including safe paths, report-list equivalence, byte lengths and SHA-256 digests, passed verification.
- Python compilation, JavaScript syntax, publishing shell syntax, Docker Compose YAML parse, repository hygiene and generated catalogue/assessment/test/dependency manifests were checked locally.

These counts describe software tests and curated checklist inventory—not the number of vulnerabilities found and not a standards certification.

## Explicitly unverified

Bandit, `pip-audit`, Docker image build, hosted GitHub Actions and hosted CodeQL were not run in the build environment. The workbook is a static offline snapshot; use the live API/dashboard for current database state. `project_key` is not tenant authorization. Standards edition applicability and exact clause-level mappings require review against the current official/licensed sources.
