# CybSec-AI Project Charter

## Mission

CybSec-AI exists to become a trusted cyber security AI assistant for defenders, analysts, responders, engineers, executives, students, and security teams.

The goal is simple:

**See Everything. Trust Nothing.**

The primary product is the hosted web app. The Local Case Kit is an optional protected Windows runtime for large or sensitive evidence/data files that should remain on a responder workstation or local network. macOS and Linux local packages are not supported yet.

Cyber security deserves an AI system built specifically for defensive work. Most AI tools are general-purpose assistants with cyber security bolted on. CybSec-AI is being designed in the other direction: cyber security first, with reasoning, evidence handling, training, triage, and safe research built around how defenders actually work.

The core reason for the project is to make high-quality cyber security help more available. New professionals should be able to learn faster. Experienced defenders should be able to triage faster. Small teams should be able to get structured guidance without needing a full security operations center. The community should have a safe place to help shape what a world-class cyber security AI should understand.

## Product Direction

CybSec-AI focuses on authorized defensive cyber security work:

- Understand cyber security questions in plain language.
- Research and explain defensive concepts clearly.
- Help analyze evidence and uploaded artifacts.
- Build incident timelines and triage summaries.
- Map findings to security frameworks and controls.
- Recommend practical remediation and validation steps.
- Teach users through reputable training paths.
- Improve through feedback, evaluations, and public beta learning.

It is intended to become a broad cyber security front door for:

- General cyber security questions.
- Threat intelligence and exposure review.
- Incident-response and cyber triage workflows.
- Malware and suspicious activity guidance.
- Secure configuration and product-specific how-to support.
- Vulnerability management and validation planning.
- Framework and compliance crosswalks.
- Training paths for beginners through advanced practitioners.
- Optional Local Case Kit evidence review when hosted upload is not appropriate.

It is not intended to become a platform for destructive activity, unauthorized exploitation, credential theft, malware operation, or bypass guidance.

## The Future Of Defensive AI

The future of cyber security AI should not be an untrusted chatbot guessing from scattered snippets. It should be measured, evidence-aware, privacy-conscious, continuously evaluated, and shaped by the defensive community.

CybSec-AI is moving toward that model:

- Better ask understanding before answering.
- Better source grounding and official-doc research.
- Better upload and artifact analysis.
- Better incident timelines, findings, and remediation plans.
- Better learning paths and analyst education.
- Better feedback loops from real beta users.
- Better evaluation coverage so quality is measured, not guessed.

The ambition is high: a free, trusted, world-class cyber security AI assistant for authorized security work. Getting there requires community feedback, careful safety boundaries, and constant testing against real defender workflows.

## Public Beta Principles

- Be useful to new and experienced security professionals.
- Put direct answers, findings, and recommended actions first.
- Separate evidence from assumptions.
- Prefer official public sources when possible.
- Avoid inventing products, citations, or findings.
- Keep private user evidence out of public discussion.
- Refuse unsafe exploit, credential theft, evasion, malware operation, or unauthorized activity.

## Community Role

The community can help by sharing:

- Questions CybSec-AI should understand.
- Places where answers were too generic or misrouted.
- Public sources that should be cited.
- File types and security artifacts that need better analysis.
- Training resources and learning paths.
- UI/UX issues from real beta use.
- Public-safe test cases and expected answer shapes.

## Protected Product Boundary

This public repo is for community collaboration only. It is not a source-code release.

The following remain private:

- Production source code.
- Upload analyzer implementation.
- Admin console internals.
- Proprietary routing, scoring, and evaluation logic.
- Model orchestration and prompt internals.
- Deployment configuration.
- Internal datasets, logs, beta-user data, and local evidence.

## Success Criteria

CybSec-AI should be judged by whether it helps users make better defensive decisions:

- Did it understand the ask?
- Did it answer the real question?
- Did it present evidence and uncertainty clearly?
- Did it provide practical next steps?
- Did it avoid unsafe or unsupported guidance?
- Did it help the user learn or respond faster?
