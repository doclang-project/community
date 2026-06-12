# DocLang Project Charter

## 1. Mission

The mission of the DocLang project is to define, maintain, and promote an open, AI-native data format for representing the content, structure, layout, and governance of documents — and to drive that format toward formal international standardization (ISO).

DocLang aims to be for documents what PDF was for printing and what JSON is for data interchange: a single, interoperable abstraction layer between unstructured documents and the AI systems that consume them.

## 2. Scope

In scope:

- The DocLang specification: syntax, semantics, conformance levels, and versioning.
- The reference grammar, schemas, and validation tooling.
- Reference implementations and conformance test suites.
- Conventions for governance metadata embedded in DocLang documents (privacy limits, extraction scopes, model-training permissions).
- Working-group output toward ISO submission.

Out of scope:

- Commercial products that consume or produce DocLang.
- Proprietary extensions to the format. Vendors are free to ship extensions, but they are not part of the standard unless adopted through the process in [GOVERNANCE.md](./GOVERNANCE.md).

## 3. Founding members

The founding members of the DocLang consortium are (in alphabetical order):

- ABBYY
- Forgis
- HumanSignal
- IBM
- NVIDIA
- Red Hat

## 4. Governance

Participation levels and individual roles are described in [MEMBERSHIP.md](./MEMBERSHIP.md). Day-to-day governance and current role holders are described in [GOVERNANCE.md](./GOVERNANCE.md).

The Technical Steering Committee (TSC) has final authority on technical direction. The TSC includes representation from each founding member to preserve vendor neutrality.

## 5. Decision-making

The project operates by **lazy consensus** for routine decisions. Substantive decisions — including specification-breaking changes, new releases of the standard, governance changes, and admission of new Member organizations — require a TSC vote. A two-thirds majority of cast votes is sufficient unless [MEMBERSHIP.md](./MEMBERSHIP.md) specifies otherwise.

Working groups may be chartered by the TSC to develop specific areas of the specification and report back with recommendations.

## 6. Licensing

- The specification text, reference implementations, and tooling are licensed under the [Apache License, Version 2.0](./LICENSE).
- Contributions are subject to the project [IP Policy](./IP-POLICY.md), which provides the patent grant and contribution-licensing terms required for an ISO-track standard.
- All contributions require a Developer Certificate of Origin (DCO) sign-off as described in [CONTRIBUTING.md](./CONTRIBUTING.md).

## 7. Antitrust and code of conduct

All project activities are conducted under the [Code of Conduct](./CODE_OF_CONDUCT.md). Member organizations and individual participants are expected to comply with applicable antitrust and competition law; the project does not coordinate on pricing, market allocation, or other competitively sensitive matters.

## 8. Hosting

DocLang is hosted under LF AI & Data, a Linux Foundation project. The project's governance and IP policy operate in accordance with LF AI & Data's requirements and conventions.

## 9. Amendments

This charter may be amended by a two-thirds vote of the TSC. Amendments take effect on merge of the corresponding pull request to this repository.
