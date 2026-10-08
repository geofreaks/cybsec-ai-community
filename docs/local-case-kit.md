# Local Case Kit

CybSec-AI is web-first. The Local Case Kit is a protected runtime package for running CybSec-AI locally only when hosted upload limits or evidence sensitivity make browser upload impractical.

Use it for:

- Large incident folders.
- Sensitive evidence.
- USB/offline response.
- Local-network case review.
- File hashing and folder manifests.
- Analysis of logs, configs, scanner exports, SIEM/EDR exports, firewall files, email headers, timelines, and triage summaries.

The kit is not an open-source source-code release. It is distributed as a protected runtime package with checksums and local-use documentation, and users do not need private GitHub repository access to download or run it.

Startup includes a read-only local readiness check for common workstation blockers before Docker starts. It reports visible AV/EDR products, Microsoft Defender status when available, Controlled Folder Access, required local ports, Docker CLI availability, and local evidence write access. It does not disable security tools, add exclusions, bypass EDR, or change host policy.

## Platform Support

- Hosted web app: supported from modern desktop and mobile browsers.
- Local Case Kit: Windows with Docker Desktop is the supported local runtime today.
- macOS and Linux local packages are not supported yet.

Download the latest official kit from the public beta page:

- https://www.cybsec-ai.com/

Look for **Local copy**.

Release checksum and deployment status: [Quality status](quality-status.md). Prepared and tested builds are distinguished from hosted downloads.

First install/build requires internet for Docker images and dependencies. Provision and test before disconnecting. The kit generates private role tokens on first startup and preserves an existing `.env`; keep that file private. Internet research defaults to disabled and can be explicitly enabled in local configuration.

Folder analysis uses a read-only Docker mount:

```powershell
powershell -NoProfile -File .\scripts\analyze-local-case.ps1 -CasePath C:\Cases\IR-001 -Json
```

Processing is bounded. Large containers may be hashed/referenced rather than deeply decoded, and partial text analysis is disclosed. No claim of unlimited sizes or complete interpretation of every forensic artifact is made.

Compiled bytecode reduces casual source exposure but is not encryption, tamper-proofing, or protection against reverse engineering. A matching checksum does not establish a publisher signature.
