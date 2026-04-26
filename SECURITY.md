# Security Policy

Sovereign System Architecture is maintained as a public-facing flagship authority hub for sovereign AI, zero-trust systems, privacy-first architecture, and enterprise automation. This policy defines how security concerns should be reported, what is in scope for public review, and which implementation details must remain private.

## Public Edition Security Scope

This repository represents the Public Edition of Sovereign System Architecture. Public materials may include positioning, documentation, static previews, high-level architecture language, governance files, non-operational examples, and safe evaluation materials.

This repository must not disclose or request disclosure of:

- private client architectures, customer environments, infrastructure maps, or internal network diagrams
- production deployment methods, access-control policies, trust-boundary rules, or hardening playbooks
- private AI prompts, system prompts, agent instructions, model configuration, or evaluation traces
- API keys, tokens, OAuth credentials, service-account files, secrets, or environment variables
- private compliance evidence, audit workpapers, risk assessments, DORA/NIS2/GDPR records, or regulator-facing materials
- private integrations with cloud accounts, identity providers, internal databases, SIEM/SOC tools, or enterprise systems
- confidential commercial implementation details, acquisition materials, pricing models, or buyer-specific requirements
- operational runbooks, incident-response plans, or security-control procedures that are not intentionally published

## Supported Scope

Security reports are welcome for issues affecting public repository materials, including:

- accidental exposure of secrets or sensitive data
- unsafe public documentation that could enable misuse
- vulnerable public demo code, if present
- dependency, supply-chain, or build configuration concerns, if such files are later added
- misleading security, compliance, sovereignty, or architecture claims that could create user or buyer risk
- repository configuration issues that affect integrity, trust, or disclosure handling

## Out of Scope

The following are generally out of scope unless they expose sensitive data or create direct user risk:

- generic best-practice requests without a specific security impact
- social engineering, phishing, or physical security testing
- denial-of-service testing or traffic flooding
- scanning infrastructure not owned or explicitly authorized by the maintainer
- automated reports with no exploitability explanation
- third-party platform issues outside this repository owner's control
- requests for private client architecture, production implementation, prompts, controls, compliance evidence, or deployment details
- speculative compliance claims without a concrete repository risk

## Reporting Process

Please report security issues privately and with minimal sensitive detail.

Preferred process:

1. Use GitHub private vulnerability reporting if it is enabled for this repository.
2. If private vulnerability reporting is unavailable, contact the maintainer through the public GitHub profile or the commercial contact path listed in SUPPORT.md.
3. Do not open a public issue containing secrets, exploit details, private architecture, prompt details, customer information, infrastructure references, or implementation-sensitive information.
4. Include a concise description, affected file or area, reproduction notes where safe, and recommended remediation.

## Response Timeline

The maintainer will make a reasonable effort to follow this timeline:

- Acknowledgement: within 5 business days
- Initial triage: within 10 business days
- Remediation decision: based on severity, exploitability, and public safety impact
- Public disclosure: only after remediation or explicit maintainer approval

This repository is maintained as a public authority and governance surface. Response times may vary for non-critical documentation findings.

## Safe Harbor

Good-faith research is welcome when it is defensive, limited, and respectful of the boundaries above. The maintainer will not pursue action against researchers who:

- act in good faith and avoid privacy violations
- do not access, modify, delete, or exfiltrate data
- do not disrupt services or third-party systems
- avoid public disclosure before coordination
- stop testing and report promptly after identifying a potential issue

Safe harbor does not apply to unauthorized access, credential misuse, data theft, extortion, prompt extraction, evasion, persistence, offensive testing against third-party systems, or attempts to obtain Private Enterprise Edition materials.

## Public Disclosure

Public disclosure should be coordinated with the maintainer. Reports may be acknowledged in release notes or changelog entries when doing so does not reveal sensitive security information.

## Responsible Use

Sovereign System Architecture is intended for lawful architecture review, sovereign AI strategy, zero-trust design, privacy-first engineering, compliance-aware evaluation, and enterprise product discussion. Reports, issues, pull requests, or discussions that enable unauthorized activity, credential misuse, unsafe deployment, compliance misrepresentation, or private implementation extraction may be closed or removed.