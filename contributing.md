# Contributing

Contributions that improve the accuracy, usefulness, and curation quality of this list are welcome.

## Inclusion Criteria

- The project is open-source, public-source, or openly reusable companion infrastructure.
- It is useful for long-term companion setups rather than only one-shot chatbot interactions.
- **Read the code of every project.** Descriptions state what the code actually implements; core logic, data flow, and how far it really runs must be confirmed in the codebase.
- **New projects are scanned automatically.** When a pull request adds a project, CI runs [ClamAV](https://github.com/Cisco-Talos/clamav) (malware), [GuardDog](https://github.com/DataDog/guarddog) (malicious-code patterns), [OSV-Scanner](https://github.com/google/osv-scanner) (known vulnerable dependencies) and [OpenSSF Scorecard](https://github.com/ossf/scorecard) (project health) on the linked repository and posts the results on the pull request. Malware means rejection; other findings are checked during code review.
- It is maintained, documented, functional, and distinct from existing entries.
- **The free version must be fully usable.** Charging for convenience is fine, such as paid hosting or giving paying users new releases a version or two earlier. Projects whose free version is deliberately limited (for example, history capped at 24 hours, or core features locked behind a subscription) are not listed. Core features here means what an individual uses with their companion; charging for enterprise-only features is fine.
- **No ads in the software.** Sponsor or donation links in the README are fine.
- **Projects that issue or promote their own crypto token are not listed.** This covers token trading links in the README or software, token launchpads, and projects that run on a token. Agent wallets and payment features are reviewed case by case: they can be listed when they are one feature of the project and unrelated to promoting a token.
- Costs outside the project itself, such as model APIs, servers, and hardware, do not count as charging.
- Projects that later add paywalls to core features or add ads will be removed from the list.
- Projects that are unfinished, experimental, or unclear are tagged `verify` or `adapt`. `ready` is reserved for projects that work once installed.

## Submitting a Change

1. Search the list for duplicates and closely related projects.
2. Inspect the candidate repository's codebase, architecture, license, pricing, release state, and actual viability.
3. Add the entry to the most specific category in `README.md` and keep the description factual and verified against code. Because the list is extensive, each entry description must stay strictly under 200 characters to keep the document concise and easy to scan.
4. Use the existing language, platform, and readiness metadata format.
5. End the entry with proper punctuation and run `npx awesome-lint` before opening a pull request.
6. If you are submitting your own project, say so in the pull request, and state whether there is a paid version and what it adds.

Please update `README.zh-CN.md` when you can provide an accurate Chinese translation. Otherwise, call out the missing translation in the pull request so it can be reviewed separately.

Open an issue when proposing a new category or when the right placement is unclear.
