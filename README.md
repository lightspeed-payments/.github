# lightspeed-payments/.github

Default community health files for the `lightspeed-payments` organization.

> [!WARNING]
> This repository is **public**, as GitHub requires for organization defaults. Don't commit anything internal.

## Pull request template

[`.github/pull_request_template.md`](.github/pull_request_template.md) pre-fills the description of every new pull request in organization repositories that **don't have their own template**. GitHub checks a repository's `.github/`, root, and `docs/` folders first. If any of them contains `pull_request_template.md` (in any letter case) or a `PULL_REQUEST_TEMPLATE/` directory, that template wins and this one is ignored.

To adopt the organization template in a repository, delete its local template.

## Enforcing the template

Enforcement is opt-in per repository. The [PR description check](https://github.com/lightspeed-payments/capital-github-workflows/blob/main/docs/pr-description-check.md) in `capital-github-workflows` reads the headings from this template and fails when a pull request leaves any of them empty or leaves a checklist item unchecked.

Changing the headings here changes what that check requires in every repository that opted in.
