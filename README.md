# ORBIT Definitions SIG

A Special Interest Group (SIG) and Technical Initiative of the [OpenSSF ORBIT Working Group](https://github.com/ossf/wg-orbit), governed by the [Definitions SIG Parent Charter](https://github.com/ossf/wg-orbit/blob/main/technical-initiatives/sigs/definitions-sig-charter.md).

The Definitions SIG develops and maintains a portfolio of **definition artifacts**: specifications, criteria sets, and supporting vocabularies that open source projects and their consumers can adopt to describe and improve security posture.

**In scope:** specification and maintenance of definition artifacts (criteria, tiers, supporting definitions); documentation, mappings to external frameworks, and [Gemara](https://gemara.openssf.org/)-compliant representations; guidance for adopters.

**Out of scope:** certification, accreditation, or attestation of specific projects; user-facing software such as enforcement or scanning tooling.

## What lives here

This repository holds the SIG's **policies and procedures**. It does not hold artifacts. Each development effort lives in its own repository with its own maintainers and local governance (see below).

## Development efforts and artifacts

The parent charter (§2.1) requires this list to be prominently displayed. Anything not listed as **Released** is a draft and must not be presented as final or complete.

| Effort | Repository | Status | Maintainers |
|--------|------------|--------|-------------|
| Open Source Project Security Baseline (OSPS Baseline) | [`ossf/security-baseline`](https://github.com/ossf/security-baseline) | Released | [list](https://github.com/ossf/security-baseline/blob/main/governance/MAINTAINERS.md) |
| Open Source Project Security Templates (OSPS Templates) | [`ossf/osps-templates`](https://github.com/ossf/osps-templates) | Draft | _not yet published_ |
| CRA Baseline for Open Source Consumption (CRABFOSC) | [`ossf/crabfosc`](https://github.com/ossf/crabfosc) | Draft | _not yet published_ |
| AI Project Security Baseline | _no repository yet_ | Proposed | _none_ |

Status values: **Proposed** (under consideration), **Draft** (development initiated, pre-release), **Released** (meets the SIG's publication criteria), **Retired** (archived or superseded; no longer receiving updates).

New efforts are adopted into this table by decision of the SIG under the acceptance process, with notice to the ORBIT TSC. The ORBIT TSC has formally recommended that the SIG limit the number of definitions it accepts, to reduce maintenance overhead and reader confusion.

## Policies and procedures

The parent charter obligates the SIG to maintain the following. Each row links to the document that satisfies it, or notes that it has not been written yet.

| Obligation | Charter | Document |
|------------|---------|----------|
| Acceptance criteria for new development efforts and contributions | §2.1 | _not yet written_ |
| Publication process and criteria for drafts to become official releases | §2.2 | _not yet written_ |
| Shared release tooling used by all artifacts | §2.2 | _not yet written_ |
| Artifact status, usage, and retirement labeling | §2.3 | _not yet written_ |
| Contributor ladder (roles, appointment, terms of at most 1 year) | §3.1 | _not yet written_ |
| Decision-making process (required once three or more maintainers are active) | §3.1 | _not yet written_ |
| Governance notice for sub-project repositories | §4.5 | Inline in the [charter](https://github.com/ossf/wg-orbit/blob/main/technical-initiatives/sigs/definitions-sig-charter.md#45-sub-project-inheritance-header) |

## Governance

- **SIG Lead:** Eddie Knight, Revanite (interim)
- **Maintainership is per development effort.** Maintainer status on one artifact confers no authority over another. The SIG Lead coordinates across efforts but does not override publication-level decisions except through escalation.
- **Local governance** for each artifact must be published in that artifact's repository and must carry the governance notice from charter §4.5. Local governance may not override the parent charters.
- **Escalation:** artifact maintainers → SIG Lead → ORBIT TSC Chair → OpenSSF TAC. See charter §4.4.
- **Code of Conduct:** the [OpenSSF Code of Conduct](https://openssf.org/community/code-of-conduct/) applies to all participants.

## Licensing

The contents of this repository are prose and are licensed [CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/) (see [LICENSE](LICENSE)).

Artifact repositories follow ORBIT WG charter §7 and Definitions SIG charter §4.2:

- Code: [Apache-2.0](https://www.apache.org/licenses/LICENSE-2.0)
- Prose and documentation: [CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/)
- Data: [CDLA-Permissive-1.0](https://cdla.dev/permissive-1-0/)

Every commit must carry a Developer Certificate of Origin sign-off (`git commit -s`). Files should carry SPDX identifiers. License exceptions require WG-charter-level approval.

## Get involved

- Mailing list: [openssf-sig-orbit-definitions@lists.openssf.org](https://lists.openssf.org/g/openssf-sig-orbit-definitions)
- Slack: `#sig-security-baseline` on the [OpenSSF Slack](https://slack.openssf.org/)
- Meetings: [join via Zoom](https://zoom-lfx.platform.linuxfoundation.org/meeting/97740884759?password=5cab7229-2324-4816-81db-517812a088a9), [meeting notes](https://docs.google.com/document/d/16tL1Ln7owIRXSoCKgyYHCs9-JP9iw-ouyk8koGAeHA0/edit)
- The parent [ORBIT WG](https://github.com/ossf/wg-orbit#join-the-community) also meets and has its own Slack channel
- Contribute to an artifact directly in its repository (see the table above)
- File issues about SIG-level policy in this repository

## Antitrust Policy Notice

Linux Foundation meetings involve participation by industry competitors, and it is the intention of the Linux Foundation to conduct all of its activities in accordance with applicable antitrust and competition laws. It is therefore extremely important that attendees adhere to meeting agendas, and be aware of, and not participate in, any activities that are prohibited under applicable US state, federal or foreign antitrust and competition laws.

Examples of types of actions that are prohibited at Linux Foundation meetings and in connection with Linux Foundation activities are described in the [Linux Foundation Antitrust Policy](http://www.linuxfoundation.org/antitrust-policy). If you have questions about these matters, please contact your company counsel, or if you are a member of the Linux Foundation, feel free to contact Andrew Updegrove of the firm of Gesmer Updegrove LLP, which provides legal counsel to the Linux Foundation.
