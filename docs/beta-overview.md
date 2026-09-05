# Beta Overview

CybSec-AI is being built as a focused cyber security AI for:

- Threat intelligence.
- Exposure review.
- Incident response.
- Vulnerability triage.
- Defensive playbooks.
- Secure configuration guidance.
- Evidence upload analysis.
- Training paths.
- Report generation.

The public beta focuses on the hosted web Ask and Upload experience, public feedback, and an optional Local Case Kit path for large or sensitive evidence.

The hosted web app works from modern desktop and mobile browsers. The downloadable Local Case Kit is currently supported on Windows with Docker Desktop; macOS and Linux local packages are not supported yet.

## Current Public Status

Last public status refresh: 2026-08-30.

- Hosted web beta is the primary CybSec-AI experience.
- The latest private product build has passed its hosted smoke checks and deployment verification.
- The protected Local Case Kit is served from the CybSec-AI web app and does not require access to the private source repository.
- Latest Local Case Kit SHA-256: `e5a4256a68a58f19159d130bb8038e0ce4e79b10f270d397baeeaefab62462f6`.
- Latest ask-understanding regression: short follow-up questions should keep the prior ask context, such as an EDR recommendation followed by "which are free?".
- Community contributions should focus on misunderstood questions, public-safe test ideas, documentation, training resources, and feature feedback.

Enterprise readiness items such as OIDC provisioning, multi-tenant isolation drills, dedicated embedding/reranker providers, and full disaster-recovery restore drills remain private deployment work and are not exposed through this community repository.

## What We Want To Learn During Beta

- Which cyber security asks are misunderstood.
- Which answers need better citations or current vendor documentation.
- Which upload/file types need stronger analysis.
- Which workflows need cleaner report exports.
- Which training paths help new and experienced professionals.
- Which UI areas slow users down.

## What Stays Private

- Product source code.
- Admin console internals.
- Proprietary routing and evaluation logic.
- Upload analyzer implementation.
- Deployment configuration.
- Internal datasets and local evidence.
- Secrets, tokens, logs, and beta user data.
