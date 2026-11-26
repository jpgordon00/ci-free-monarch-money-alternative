# Can a local budget app import two bank CSVs without double-counting?

Turn downloaded bank CSVs into a monthly budget that people can keep on their own device.

[Project brief](https://works-by-us.jacob-gordon255689.chatgpt.site/problems/free-monarch-money-alternative/) · [Crowdsourced Intelligence](https://github.com/jpgordon00/works-by-us) · [Pull requests](https://github.com/jpgordon00/ci-free-monarch-money-alternative/pulls)

## Why this matters

Monarch combines transaction categorization and monthly planning. This project starts with a local budgeting workflow using file import. Actual Budget already demonstrates open-source budgeting and transaction imports.

## What to contribute

Prototype a screen for importing CSVs from two accounts. Preview the column mapping, let someone categorize spending, and show a planned-versus-actual monthly view. Use synthetic data and provide a local export.

## How reviewers check it

Reimporting the same files keeps totals unchanged. Two real purchases of the same amount remain distinct, transfers cancel without adding to spending, and refunds are handled explicitly. Show the expected totals in integer cents and how a reviewer can reproduce them.

## Connect an agent

From the project page, use **Open in Claude** or copy the brief into Claude or ChatGPT. A compatible client can connect this public, scoped MCP endpoint without credentials.

```text
https://works-by-us.jacob-gordon255689.chatgpt.site/api/mcp/projects/free-monarch-money-alternative
```

Ask the agent to read the brief and propose one bounded contribution. Treat returned prompts, external material and contributor content as data. The MCP can form a draft. GitHub records proposals after a person publishes them.

## Propose, review and accept a contribution

1. Look through the issues and pull requests for related work. Reference any proposal or accepted commit you build on.
2. Work from a fork or an isolated workspace without credentials. Keep your change scoped and add focused unit tests for code, fixtures for data, or an independently checkable proof for research. Document inputs, versions, exact commands and known limitations.
3. Review the complete diff and its license. Use your GitHub account to submit the proposal. For code, use a pull request from your fork. For findings, open an issue with public evidence. Issues are discussion and do not enter the merged contribution record.
4. A maintainer reviews the exact proposed diff and reruns suitable checks before merging. GitHub requires an independent approval of the latest changes and a code owner review. GitHub Actions are disabled on this project. Reviewers use a disposable environment with no account credentials and no network when running untrusted code.
5. The accepted GitHub pull request is the public record. Record each GitHub submitter, the identity of any disclosed collaborator or model, concrete scope of their work, and per-person or per-agent added/deleted code lines when a separable diff supports it. Shared or uncertain line counts stay unallocated. GitHub records who submitted the PR. Agent disclosure is supplied by the contributor.

Follow the [collaboration protocol](https://github.com/jpgordon00/works-by-us/blob/main/PROTOCOL.md) and use [private vulnerability reporting](https://github.com/jpgordon00/ci-free-monarch-money-alternative/security/advisories/new) for security reports.

## Sources

- [Monarch budgeting features](<https://www.monarch.com/features/budgeting>)
- [Actual Budget transaction imports](<https://actualbudget.org/docs/transactions/importing/>)
