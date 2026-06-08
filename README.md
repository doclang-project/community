# DocLang Community

Welcome to the DocLang community!

This is the starting point for becoming a contributor — improving the specification, extending docs, giving talks, building reference implementations, and more.

## Introduction

DocLang is an open, AI-native data format for representing the content, structure, layout, and governance of documents. The goal is to provide a single, standardized abstraction layer between unstructured documents (PDF, images, audio-visual, scanned files, etc.) and the AI systems that operate on them — analogous to what PDF did for printing, or what JSON did for data interchange.

DocLang explicitly preserves both **semantic meaning** (headings, paragraphs, tables, lists, formulas, code) and **geometric layout** (page coordinates, regions, reading order) in a single representation, and embeds **enforceable governance controls** (privacy limits, extraction scopes, model-training permissions) directly into the document.

The standard is being developed as an open consortium effort with the intent of ISO standardization.

## Founding members

DocLang is a multi-vendor effort. The founding members are:

- **ABBYY**
- **HumanSignal**
- **IBM**
- **NVIDIA**
- **Red Hat**

The list of named contributors to the specification is maintained in the [DocLang standard repository](https://github.com/doclang-project/doclang-standard) and reflected in [MAINTAINERS.md](./MAINTAINERS.md).

## Adopters

Organizations that have implemented the DocLang standard in a product or internal system are listed here.

*Be the first — see [MEMBERSHIP.md](./MEMBERSHIP.md#4-adopter) for how to register.*

## History

The initial draft of the DocLang specification originated from research by the AI for Knowledge team at IBM Research Europe – Zurich, building on prior work in the Docling open-source project. It has since been opened up as a vendor-neutral standard developed by the founding members listed above.

## Governance

The governance of the project is described in the [GOVERNANCE.md](./GOVERNANCE.md) file. The project [Charter](./CHARTER.md) and [Membership tiers](./MEMBERSHIP.md) describe the high-level structure, and the [IP Policy](./IP-POLICY.md) covers patent and contribution licensing — relevant for any ISO-track standard.

The Technical Steering Committee (TSC) meets regularly. Meeting notes are kept in [steering-committee/meeting-notes/](./steering-committee/meeting-notes/).

## Roadmap

The TSC maintains the overall DocLang roadmap in [docs/roadmap.md](./docs/roadmap.md).

## How can I help?

DocLang is driven by the participation of its members and the wider community. Ways to get involved:

- **Specification work** — propose changes, raise issues, and review pull requests on the [primary DocLang repository](https://github.com/doclang-project/doclang-standard).
- **Reference implementations** — build or contribute to parsers, validators, and converters.
- **Documentation, examples, tutorials** — there is always room for clearer onboarding material.
- **Adoption stories** — talks, blog posts, and case studies help the standard mature.

If you are looking for a first issue, search the [primary DocLang repository](https://github.com/doclang-project/doclang-standard/issues) for the `help wanted` label.

## Reporting security issues

Please follow the process described in [SECURITY.md](./SECURITY.md). Do not report security issues through public GitHub issues.

## Questions and discussion

For general questions and design discussion, please use the [discussions section](https://github.com/doclang-project/doclang-standard/discussions) of the primary DocLang repository.
