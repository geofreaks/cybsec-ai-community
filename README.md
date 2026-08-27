# CybSec-AI Community

**See Everything. Trust Nothing.**

This is the public community home for CybSec-AI beta feedback, cyber security question coverage, public test ideas, documentation suggestions, training resources, and responsible issue reporting.

CybSec-AI itself is a protected cyber security AI product. The production engine, routing logic, upload analyzers, admin console, deployment configuration, and proprietary model/evaluation logic remain private.

## Why This Exists

General-purpose AI is useful, but cyber security needs something more focused: a dedicated defensive AI engine built for the good guys.

CybSec-AI is being built to become a world-class, free-to-access cyber security assistant and one-stop shop for authorized, non-destructive security work. The intent is to help people understand risks, investigate evidence, learn security skills, triage incidents, review exposures, harden systems, and make better defensive decisions without turning the platform into an exploit runner or destructive tool.

The long-term vision is a trusted cyber security AI layer that combines:

- Plain-language cyber security reasoning.
- Current public security knowledge and official documentation.
- Evidence-aware upload and incident analysis.
- Defensive playbooks, training paths, and practical remediation.
- Framework mapping across ATT&CK, CIS, NIST, OWASP, PCI, CMMC, ISO, and related standards.
- Community feedback that improves coverage, clarity, and usefulness over time.

This public repo exists so the community can help shape that future safely: suggest questions, identify gaps, improve public docs, recommend training resources, and report beta issues without exposing private product code or sensitive user evidence.

## Public Beta

- Product: https://www.cybsec-ai.com/
- Contact: contact@cybsec-ai.com
- Project charter: docs/project-charter.md

## Related Project

- [TYRNEX-AI public runtime](https://github.com/geofreaks/tyrnex-ai-public) provides a local, protected security assessment, cyber triage, topology, and remediation reporting kit for authorized environments.

CybSec-AI is the AI/analyzer workbench. TYRNEX-AI is the local assessment and evidence-generation runtime. They can exchange exported evidence and reports, but neither product requires the other to run.

## What Belongs Here

Use this repo to contribute:

- Cyber security questions CybSec-AI should understand.
- Expected answer quality examples.
- Product/how-to gaps.
- Training resources and learning-path suggestions.
- Upload-analysis scenarios and sample artifact descriptions.
- UI/UX feedback.
- Bug reports from the public beta.
- Documentation improvements.

Do not submit secrets, exploit payloads, stolen data, private incident evidence, raw malware, live credentials, customer logs, or anything you are not authorized to share.

## Local Case Kit

CybSec-AI has a protected Local Case Kit for responders who need to review large or sensitive evidence on their own workstation or USB/offline kit. The kit is distributed as a protected runtime package rather than open source.

Use the public beta page's **Local copy** link to download the latest kit. The download is served from CybSec-AI itself and does not require access to the private product repository.

The Local Case Kit is intended for:

- Large incident files.
- Sensitive evidence that should stay on your workstation.
- USB/offline incident response.
- Folder-based case analysis using logs, scanner exports, firewall configs, EDR/SIEM exports, manifests, timelines, and triage output.

## Contribution Model

This repo is community-driven, but not a source release of the CybSec-AI engine.

Good contributions:

- "This question was misunderstood."
- "This answer should cite this official vendor page."
- "This firewall config type should be detected."
- "This IR report format needs these sections."
- "This training path should include these resources."

Not accepted:

- Requests to disable safety boundaries.
- Exploit/payload runbooks.
- Credential theft, phishing, bypass, or malware operation content.
- Proprietary source extraction or reverse-engineering requests.
- Private data, breached passwords, session tokens, or customer evidence.

## Repository Map

- `.github/ISSUE_TEMPLATE/bug_report.yml` - beta bug reports.
- `.github/ISSUE_TEMPLATE/ask_understanding_gap.yml` - questions CybSec-AI misunderstood.
- `.github/ISSUE_TEMPLATE/feature_request.yml` - feature or product-pack requests.
- `.github/ISSUE_TEMPLATE/upload_analysis_gap.yml` - upload/file-analysis coverage gaps.
- `docs/` - public product docs, roadmap, and beta guidance.
- `tests/public-question-seeds/` - public-safe question coverage seeds.

## License

Community docs and issue templates are shared for public beta collaboration only. CybSec-AI product code, hosted service, local runtime package, prompts, analyzers, datasets, evaluation logic, and model orchestration are proprietary and are not licensed through this repo.
