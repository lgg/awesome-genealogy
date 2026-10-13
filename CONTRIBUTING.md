# Contributing

Thanks for helping improve Awesome Genealogy. This is a **curated list**, not a complete directory; inclusion is an editorial decision based on direct relevance and usefulness, not an advertising opportunity.

## Scope and Editorial Review

- **Direct genealogy utility:** The resource must directly help people research family history; find, assess, cite, transcribe, or preserve historical records; build, manage, exchange, publish, or visualize genealogical data and family relationships; develop genealogy applications; or perform responsible genetic genealogy.
- **Generic media tools are out of scope:** General-purpose photo enhancement, AI portrait animation, video generation, greeting cards, and other family-themed creative services are not eligible solely because they can be used with ancestors' photos. A substantial, demonstrable genealogy-specific research, publishing, or data-preservation workflow is required.
- **Commercial and proprietary resources are welcome:** They must pass the same quality and direct-utility bar as open-source projects. Payment, a proprietary license, and responsible self-promotion are not grounds for automatic rejection.
- **Disclosure of affiliation:** If you authored, own, work for, represent, or are paid to promote a resource, say so in the PR. Automated/AI-agent submissions must disclose whom they represent. Disclosed self-nominations are reviewed under the same standards but are never guaranteed inclusion.
- **Verifiability:** Prefer projects that are active or appropriately marked historical, documented, reputable, accessible for independent inspection, and useful for a well-defined task. The link must work; provide a demo, documentation, or concrete examples where appropriate. Claims about offline/local-only processing or privacy-sensitive genealogical data should be supported by accessible documentation or a verifiable implementation.
- **Safety, privacy, and consent:** Do not add unauthorized personal-data dumps, doxxing resources, credential-gated data mirrors, tools for bypassing access controls, or content encouraging misuse of data about living people, records, or DNA. Respect copyright and applicable law.

## Submission Guidelines

- Use the canonical project, organization, specification, or service URL, not a mirror or download aggregator.
- Add **one resource per pull request** where practical.
- Keep resources alphabetized within their section.
- Use a concise, useful, neutral description ending in a period. Avoid marketing language, ratings, exaggerated claims, and unverified privacy assurances.
- Identify commercial, experimental, regional, or historical status when relevant.
- Move abandoned/superseded projects to **Historical Projects** rather than deleting useful references.

### Resource labels

Use the following labels **at the beginning of a resource's description** when verifiable:

- `Open Source`: source code is publicly available under an open-source license. A public code repository without an appropriate license is not sufficient proof.
- `Free`: the resource's listed core purpose is available at no charge.
- `Freemium`: a meaningful free workflow exists, but enhanced capabilities, usage, output, or related services cost money.
- `Paid`: meaningful usage requires payment, even if there is a trial or preview.

Use one of `Free`, `Freemium`, or `Paid` for applications and services when possible, and additionally `Open Source` where confirmed. These classifications are independent: an open-source program may also offer a paid hosted tier. For an archive or standard, use `Free` only when its linked main resource is freely available. Avoid unsupported assertions about licenses or pricing. Absence of `Open Source` does **not** imply proprietary source code.

Example:

```md
- [Name](https://example.com/) - **Open Source · Freemium** — Short neutral description.
```

## Quality Bar

A good entry should answer at least one of these questions:

- Does it help someone build, maintain, visualize, exchange, publish, or preserve a family tree or evidence attached to it?
- Does it help researchers find, evaluate, cite, organize, transcribe, or publish historical records?
- Does it help developers implement genealogy software, integrations, APIs, or interoperable data formats?
- Does it support genetic genealogy with clear privacy and consent expectations?

Simply being useful for family activities or photo-based gifts is not enough to meet this bar.

## Running Checks

Run the linter before submitting:

```sh
npx awesome-lint
```
