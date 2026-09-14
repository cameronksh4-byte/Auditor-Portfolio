# Auditor-Portfolio

A public, sanitized portfolio of AI governance / AI risk audit work produced through a self-directed audit training simulator, built to develop and demonstrate real audit-execution skill: scoping, evidence handling, control testing, findings, and reporting for AI use in small and medium-sized businesses.

## Purpose

Every engagement in this repo started as a simulated audit against a fictional SMB client, run as a realistic engagement rather than a quiz — discovery through interviews, evidence requested (not handed over), control testing, findings development, and a closing meeting with management pushback. This repo holds the sanitized, publishable output of that process.

## Skills demonstrated

- Audit scoping and criteria selection (distinguishing legal/regulatory requirements from contractual obligations, internal policy, and voluntary frameworks)
- AI system inventory and AI exposure assessment, including shadow AI and vendor-introduced AI
- Evidence-based audit practice — distinguishing management assertion from evidence and corroboration
- Control design vs. implementation vs. operating-effectiveness testing
- Risk-based finding severity determination
- Audit reporting and stakeholder communication, including handling of management disagreement

## Methodology

Engagements draw on recognized frameworks and standards as appropriate to each scenario, including the NIST AI Risk Management Framework and Playbook, NIST Cybersecurity Framework, ISO/IEC 42001 and 23894 concepts, relevant information-security and privacy principles, OWASP guidance for AI/LLM systems, third-party/vendor risk-management principles, and applicable law where the scenario's jurisdiction and use case make it relevant. See `/methodology/` for the working approach.

## Frameworks referenced

- NIST AI RMF / Playbook
- NIST Cybersecurity Framework
- ISO/IEC 42001, ISO/IEC 23894
- OWASP (AI/LLM-relevant guidance)
- General privacy and vendor-risk principles

Not every framework is claimed as applicable to every engagement — see each case study's `scope.md` for the specific criteria used and why.

## Ethical handling of simulated data

- Every organization, person, and dataset in this repo is fictional. No real company, employee, or client is represented, named, or implied.
- No real confidential information, credentials, or personal data appears anywhere in this repo.
- Each case study is drawn from a private working-paper trail that also records private training feedback (mistakes made, coaching received, competency scoring). That private material is deliberately excluded from this repo — see each case study's README for what was left out and why.
- Nothing here should be read as a claim that any real organization was audited or failed an audit.

## Portfolio organization

```
/README.md
/methodology/        - working audit approach and criteria-selection notes
/templates/           - sanitized, reusable audit templates
/simulations/          - individual simulated engagements, one folder per engagement
/case-studies/          - completed, written-up engagements in case-study form
/findings-examples/     - illustrative findings pulled from completed engagements
/risk-assessments/       - example AI risk assessments
/control-testing/         - example control testing workpapers
/lessons-learned/          - lessons approved for public sharing (see note below)
/framework-mapping/         - notes mapping engagement work back to NIST AI RMF / ISO 42001 / etc.
```

**A note on "lessons learned":** this repo distinguishes a private training deficiency ("the auditor failed to corroborate a management assertion") from a public lesson learned ("corroborating management assertions with operational evidence proved important when evaluating this control"). Only the latter appears here, and only once it's been reviewed and approved for publication.

## Status

This repo is actively being built out as engagements are completed and approved for publication. Folders may be sparse or placeholder-only until the first engagement finishes.
