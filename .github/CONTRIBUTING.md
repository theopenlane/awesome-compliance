# Contribution guidelines

Awesome Compliance lists the tools, platforms, frameworks, and primary sources a governance, risk, and compliance (GRC) practitioner would recommend to a peer, and leaves out the rest. Most pull requests we close are closed for one reason: the entry is real, but nobody other than its author has recommended it yet.

Read [the curation policy](CURATION.md) before opening a pull request. It is the bar we apply, and every close message cites it.

## What we list

Frameworks and standards link to the official publisher's page for a standard, regulation, or control framework. Legislative and regulatory entries link to primary legal texts and the official or widely used reference sites for them.

Open source platforms and tools have a recognized open source license, a public repository, documentation, and evidence that people other than the author use them.

Commercial platforms are products a practitioner in the field already recognizes. Mark them `(Commercial)` or `(Freemium)`.

Compliance specifications and resources are machine-readable formats, control catalogs, and reference material published by a standards body, an auditor, or an established community.

Regulatory data sources give programmatic access to filings, registries, and enforcement records, with the method and provenance published.

## What we do not list

* Blog posts, guides, checklists, ebooks, newsletters, courses, or podcasts
* Policy templates and template packs, including free ones (we do not link our own)
* Products or repositories less than 30 days old, or with no public track record
* A second entry from the same vendor in the same category
* Consulting services, agencies, and done-for-you offerings
* Anything whose linked page is a lead-capture form or a landing page for a paid product

## How to submit

1. Search the list for the name and the domain. We close duplicates
1. Add one entry per pull request. We close multi-entry pull requests unless every entry stands on its own and the pull request says why each one belongs
1. Title the pull request `Add <Name>`
1. Use the format `- [Name](url) - Description.` (the README uses `-` list markers and the linter requires them to stay consistent) with a spaced hyphen, an uppercase first letter, and a period at the end. No em dashes. One link per entry; a secondary `([GitHub](url))` at the end is fine for a project whose main link is its site
1. Describe the project, not the entry. Say what it does and for whom in one or two sentences. No marketing language, no superlatives, and no numbers the linked page cannot back
1. Place the entry at the bottom of the right category. Do not create a new section for a single entry
1. Make the case in the pull request body. Answer what it does that the nearest existing entry does not, who other than the author uses it, and where a practitioner would find it referenced. We close a pull request whose body only restates the description
1. Disclose affiliation. We welcome self-submissions and hold them to the same bar as third-party nominations. We close for undisclosed affiliation
1. Run `npx awesome-lint` (Node 20 or newer) before opening the pull request
1. Write the pull request yourself. We close fully generated pull requests without review, per the upstream awesome guidelines

## What happens next

A maintainer applies [the curation policy](CURATION.md) and either merges, asks for a specific change, or closes with the reason and the rule it cites. A close is not a judgement on the project. It means the evidence is not there yet, so reopen when it is.

## Fixing existing entries

Pull requests that fix a dead link, a wrong description, a spelling error, or an entry that no longer meets the bar are always welcome, and they are the fastest way to get merged.
