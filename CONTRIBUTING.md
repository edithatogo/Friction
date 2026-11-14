# Contributing to Friction

Contributions support research into how court judgments reach the public, with an emphasis on source access, publishing processes, and evidence for service improvements.

## Before you start

Read the [project description](README.md). Identify the jurisdiction, publishing organization, process stage, and time period addressed by a proposed change. Separate observations about current practice from recommendations for future services.

Search existing issues and pull requests to avoid duplicating work. Describe substantial proposals before implementation, and use repository issue or pull request templates when available. Small corrections can go directly into a focused pull request.

For bug reports, include the affected version or commit, environment, minimal reproduction, expected and actual behavior, and sanitized diagnostics. For feature requests, explain the use case and intended outcome.

## Development and validation

The current tree is a research description, without a software package or defined test runner. Validate documentation through source checks, rendered Markdown inspection, and clear references. Record document dates and precise locators so that a reader can trace each substantive factual claim.

For data or process maps, explain collection methods, coverage gaps, missing records, and assumptions. Use public or synthetic examples and preserve applicable copyright, privacy, and publication restrictions. Access to a court document does not by itself establish permission to republish all its content.

For any new implementation, add a documented environment, small representative fixtures, and a repeatable validation method. Keep speculative proposals and verified findings visibly distinct, and record checks that remain unperformed.

Update affected documentation and examples alongside behavior changes. Add a focused regression case for a bug fix where executable tests are appropriate. Record checks that were not run and the reason.

## Submitting a pull request

Create a focused branch from the current `master` branch and open a pull request back to it. Keep unrelated formatting, refactoring, and dependency changes separate.

Include:

- The problem, proposed change, and resulting behavior.
- Related issues or existing track references.
- Exact validation commands or inspection steps, results, and limitations.
- Compatibility implications and any data or dependency provenance.

Inspect the complete diff before submission. Required automated checks must pass before merge. Follow the existing repository and account policies; this guide does not introduce a second-person approval requirement or relax existing checks.

## Security and sensitive information

Follow the [account security policy](https://github.com/edithatogo/.github/blob/main/SECURITY.md). Report vulnerabilities privately through GitHub's **Report a vulnerability** option if available. Otherwise request a private reporting contact without disclosing the vulnerability publicly. Keep credentials, personal data, and unredacted logs out of commits, issues, and examples.

## Licensing and conduct

Preserve existing attribution and applicable source or package terms. This guide does not grant a new license. Submit only material you are entitled to contribute, and document unclear permissions before adding third-party content. Follow the [account code of conduct](https://github.com/edithatogo/.github/blob/main/CODE_OF_CONDUCT.md). This guide adds no CLA, mandatory sign-off, or relicensing condition.

## Reference guidance

- [GitHub contributor guidelines](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/setting-guidelines-for-repository-contributors)
- [OpenSSF Best Practices criteria](https://www.bestpractices.dev/en/criteria)
