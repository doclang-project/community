# Participation

DocLang defines participation levels for organizations and roles for individuals.

## Participation levels for organizations

Participation levels for organizations are structured in a cascade of increasing levels of rights and obligations, as defined further below.

### Adopter level

An **Adopter** organization is an organization that is using the DocLang standard in a product or internal system.

#### Rights

- Logo and listing on the project website and README
- Early access to draft spec versions before public release
- Formal roadmap input channel — submissions are acknowledged by the TSC
- Featured in adopter showcases in releases, blog posts, and events
- Conformance recognition *(planned — pending availability of the conformance test suite)*

#### Obligations

- Self-identify as a user of the standard
- Comply with the [Code of Conduct](./CODE_OF_CONDUCT.md)

#### Process

Open a GitHub issue using the [Adopter Registration template](https://github.com/doclang-project/community/issues/new?template=adopter-registration.md). A TSC member will acknowledge and coordinate your listing.

### Contributor level

A **Contributor** organization is an Adopter that additionally contributes to the project by submitting issues, proposals, or pull requests.

#### Rights

In addition to those of an Adopter:
- Recognition as a contributing organization
- Eligible to be nominated as a Member organization

#### Obligations

In addition to those of an Adopter:
- Sustained commitment to the project
- Comply with the [IP Policy](./IP-POLICY.md) and [Code of Conduct](./CODE_OF_CONDUCT.md)

#### Process

Open a GitHub issue using the [Contributor Registration template](https://github.com/doclang-project/community/issues/new?template=contributor-registration.md). A TSC member will acknowledge and coordinate your listing.

### Member level

A **Member** is a Contributor organization *formally* participating in the DocLang consortium. A Member organization makes regular, ongoing contributions to the specification, reference implementations, or documentation.

#### Rights

In addition to those of a Contributor:
- Consortium membership standing
- Eligible to designate participation in consortium activities as defined by the TSC

#### Obligations

In addition to those of a Contributor:
- Sustained, regular engagement with the project
- Comply with the [IP Policy](./IP-POLICY.md) and [Code of Conduct](./CODE_OF_CONDUCT.md)

#### Process

Admission of new Member organizations requires a 2/3 vote of the TSC.

## Roles for individuals

DocLang differentiates between steering and technical roles for individuals, as specified further below. Holding any steering role and holding any technical role are independent of each other.

### Steering roles

#### Technical Steering Committee (TSC)

The **Technical Steering Committee (TSC)** is the governing body of DocLang. TSC members hold final authority on technical direction, spec releases, governance changes, and TSC admissions.

##### Who

- **Founding member representatives** — each founding member designates at least one TSC representative.
- **Elected TSC members** — any individual may be nominated for a TSC seat by an existing TSC member and elected by a 2/3 majority TSC vote.

##### Rights

- Vote on all substantive matters: spec-breaking changes, new releases, governance amendments, new TSC members

##### Obligations

- Active contribution to and promotion of the project
- Founding members must maintain at least one designated TSC representative
- Comply with the [IP Policy](./IP-POLICY.md)

##### Process for elected TSC members

An existing TSC member nominates a candidate. A 2/3 majority of cast TSC votes is required for admission.

##### TSC Chair

The TSC Chair ensures the smooth running of the TSC. The Chair does not have additional voting power.

Current TSC members are listed in [GOVERNANCE.md](./GOVERNANCE.md#technical-steering-committee-tsc).

##### Decision-making

Routine decisions operate by lazy consensus. Substantive decisions — spec-breaking changes, new releases, governance amendments, new TSC members — require a 2/3 majority of cast votes.

### Technical roles

Technical roles are structured in a cascade of increasing levels of rights and obligations, as defined further below.

#### Contributor

A **Contributor** is any individual who engages with the project by submitting issues, proposals, or pull requests. There is no formal process — see [CONTRIBUTING.md](./CONTRIBUTING.md) to get started.

##### Rights

- Submit issues and pull requests on any DocLang repository
- Participate in design discussions
- Eligible to be nominated as a Committer

##### Obligations

- DCO sign-off on all contributions (see [CONTRIBUTING.md](./CONTRIBUTING.md))
- Comply with the [Code of Conduct](./CODE_OF_CONDUCT.md)

#### Committer

A **Committer** is a Contributor who has been formally recognized by the TSC as a sustained, regular participant.

##### Rights

In addition to those of a Contributor:
- Write access to DocLang repositories
- Participate in and lead working groups
- Eligible for TSC nomination

##### Obligations

In addition to those of a Contributor:
- Sustained, regular engagement with the project
- Comply with the [IP Policy](./IP-POLICY.md) and [Code of Conduct](./CODE_OF_CONDUCT.md)

##### Process

A Committer candidate is nominated by any TSC member. The TSC acknowledges the nomination via lazy consensus (any TSC member may raise an objection within 7 days; silence is assent) — no formal vote required.

Current committers are listed in [GOVERNANCE.md](./GOVERNANCE.md#committers).

#### Maintainer

A **Maintainer** is a Committer responsible for a specific DocLang repository.

##### Default roster

The [default maintainer roster](./GOVERNANCE.md#maintainers) applies to any DocLang repository — unless overridden by a per-repository override.

##### Per-repository overrides

A repository may publish a `MAINTAINERS.md` file to override the default roster.

##### Rights

In addition to those of a Committer:
- Review and merge pull requests for the repositories they maintain.

##### Process

Maintainers are appointed by the TSC, in consultation with existing maintainers. Changes to the default roster require TSC acknowledgement via lazy consensus; per-repository overrides are recorded in that repository's `MAINTAINERS.md`.

## Resignation and removal

Any participant may step down at any time by notifying the TSC. Participants may be removed by a 2/3 vote of the TSC for material breach of the [Code of Conduct](./CODE_OF_CONDUCT.md) or [IP Policy](./IP-POLICY.md).

Founding member seats are permanent; however, a founding member may resign its seat by written notice to the TSC. A vacant founding member seat may be filled by a 2/3 TSC vote.

## Amendments

This document may be amended by a 2/3 vote of the TSC, in coordination with LF AI & Data where applicable.
