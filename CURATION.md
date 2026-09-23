# Curation policy

Every entry on Awesome Compliance must meet this bar. Maintainers apply it to every pull request and cite it in every close, and contributors should read it before submitting. It extends the [upstream awesome guidelines](https://github.com/sindresorhus/awesome/blob/main/pull_request_template.md), which remain the floor.

## Scope

Resources for people who operate a compliance program: compliance officers, risk managers, auditors, security engineers with a compliance mandate, and founders facing their first audit. Primary frameworks are SOC 2, the ISO 27001 family, NIST, PCI DSS, HIPAA, GDPR and EU digital regulation, SOX, and ESG disclosure. Adjacent topics (general security tooling, privacy engineering, AI governance) are in scope only where the entry's purpose is producing or evidencing compliance.

## The test

We list an entry when a maintainer could recommend it to a peer and explain why in one sentence. That means it passes every gate, shows at least two independent signals with at least one from S1 to S5, and hits no disqualifier.

### Gates

| ID | Gate |
| --- | --- |
| G1 | The link resolves to the thing described |
| G2 | It fits the scope above and an existing category |
| G3 | It is not already listed, by name or domain |
| G4 | It is maintained: pushed within 12 months, not archived or deprecated, and services are live |
| G5 | It is documented well enough to evaluate without contacting the author |
| G6 | Open source has a recognized license file, data states its terms, and commercial says so |
| G7 | It has existed publicly for at least 30 days before the pull request, with more than a first commit |
| G8 | The entry text and pull request follow the format rules in the [contribution guidelines](CONTRIBUTING.md) |

### Signals

| ID | Signal | What counts |
| --- | --- | --- |
| S1 | Adoption | Stars, downloads, or customers notable relative to the best entry in the same category (fresh-account stars do not count) |
| S2 | Community | More than one substantive contributor, or issues and pull requests from non-authors |
| S3 | Independent reference | Cited by a standards body, an auditor, another curated list, or a practitioner source the vendor does not control |
| S4 | Longevity | Six months of sustained activity or a published version history |
| S5 | Third-party nomination | Submitted by someone unaffiliated with the project |
| S6 | Unique capability | Does something no existing entry in the category does, and the pull request says what |
| S7 | Primary source | Is the official publisher, or derives from one with method and per-record provenance published |
| S8 | Maintainer vouch | A maintainer or a trusted practitioner has used it |

### Disqualifiers

| ID | Disqualifier |
| --- | --- |
| D1 | Repository, account, or domain created within days of the pull request |
| D2 | Generated boilerplate: README, site, and pull request read as model output, with claims and no examples |
| D3 | Content marketing: a guide, checklist, template pack, tracker page, or free tier that exists to funnel to a paid product |
| D4 | Bulk or serial submission: many entries from one vendor, or a resubmission after a close under a new account or name |
| D5 | Placement inflation: a new subsection for one vendor, or an entry in a section it does not fit |
| D6 | Claims in the description that the linked page does not substantiate |
| D7 | Unsafe or misleading: encourages practices that fail audits, misstates legal obligations, or scrapes sources against their terms |
| D8 | Link farm: the page is mostly links, or the project is itself a list of lists |

## Category bars

Each category adds a requirement on top of the test.

### Open source platforms

Needs S1 or S2 in addition to any other signal. A single-author repository with no external issues or stars is not yet a platform, however good the code. We hold agent-governance and AI audit-trail SDKs to this strictly because the category has filled with sub-100-star, single-vendor entries, and a new one must show why it displaces one already listed.

### Commercial platforms

Needs S1 or S3 at a level a practitioner recognizes without a search. A description of features is not evidence. One entry per vendor. Freemium products are commercial products with a free tier, and we judge them as commercial.

### Compliance specifications and resources

Needs S7 or S3. Reserved for machine-readable formats, control catalogs, crosswalks, and reference material from a standards body, an auditor, or a community with non-author contributors. Not for templates, answer banks, or methodology documents from a single vendor.

### Regulatory data sources

Needs S7: derived from an official register or filing system, with method, per-record source links, and update cadence published. Whether access is free or pay-per-use does not affect the decision. One entry per vendor; a vendor with many country-specific products gets one entry linking to its catalog. A new geographic subsection requires at least two independent, established sources. A static export of a few dozen rows is a publication, not a data source, and fails under D3.

### Regulation-specific tools

Tools for the EU AI Act or any other regulation go in Tools & Platforms, not under the regulation's heading in Legislative & Regulatory. That section is for the laws and their official references.

## Self-submissions

We welcome self-submissions because tool authors know their tools best. Disclose the affiliation in the pull request body. The rubric is identical. Undisclosed affiliation that a maintainer discovers fails under D6 and closes the pull request.

## Existing entries

Entries merged before this policy are subject to it. A periodic audit lists entries that fail a gate or hit a disqualifier, and maintainers remove them in a single pull request with the audit as the rationale. Anyone may open a removal pull request citing this document.

## How maintainers respond

Every close names the gate, signal shortfall, or disqualifier by ID and says what would change the outcome. Closed pull requests are the worked examples of this policy, so contributors should read the last ten before submitting.
