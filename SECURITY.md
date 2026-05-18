# Security Policy

The DocLang project takes the security of the specification and its reference implementations seriously. This document describes how to report vulnerabilities and what to expect after reporting.

## Scope

This policy covers:

- The DocLang specification (e.g. parser-exploitable ambiguities, governance-control bypass conditions).
- Reference implementations maintained under the [doclang-project](https://github.com/doclang-project) GitHub organization.
- Tooling and validators published under the same organization.

Out of scope:

- Third-party tools or libraries that consume DocLang but are not maintained by the project.
- Vulnerabilities in upstream dependencies — please report those to the relevant upstream project.

## Reporting a vulnerability

**Please do not report security issues through public GitHub issues, discussions, or pull requests.**

Send vulnerability reports privately to:

<!-- TODO: security@doclang.org -->

Please include, as much as is practical:

- A description of the issue and its potential impact.
- Steps to reproduce, including a minimal example DocLang document or input where applicable.
- The affected specification version, implementation, or commit.
- Whether the issue is already public, and any disclosure deadline you require.

You should receive an acknowledgement within **5 business days**. If you do not, please follow up — your message may not have been received.

## Coordinated disclosure

The project follows a coordinated-disclosure model:

1. We acknowledge the report and begin investigation.
2. We confirm or refute the issue and assess severity (typically using CVSS v3.1).
3. We develop a fix or specification clarification, coordinating with affected implementations.
4. We agree a disclosure date with the reporter. The default embargo is **90 days** from the initial report, shorter if a fix is ready earlier, longer only by mutual agreement.
5. We publish an advisory and credit the reporter (unless they prefer to remain anonymous).

## Safe harbor

We will not pursue legal action against good-faith security researchers who:

- Make a sincere effort to avoid privacy violations, service disruption, or data destruction.
- Only interact with systems they own or have explicit permission to test.
- Give us reasonable time to investigate and remediate before public disclosure.

## Contact

Security contact: <!-- TODO: security@doclang.org -->

General project contact: see [GOVERNANCE.md](./GOVERNANCE.md).
