# Git Commit Signature

Test repo to try different cases using GPG signatures with Git commits.

## Examples using GitHub GUI buttons

For these examples, the PR was merged using the GitHub GUI.

### Batch 01

Requirements:

- Committer and author are the same.
- GPG key identity (user and email) is the same as the committer.
- No pull request. Push directly to the `main` branch.

Examples:

- [Example 01: committer and author are the same](https://github.com/josecelano-test/git-commit-signature/issues/1)

### Batch 02

Requirements:

- Committer and author are the same.
- GPG key identity (user and email) is the same as the committer.
- PR using branches in the same repo.

Examples:

- [Example 02: pull request with a merge commit](https://github.com/josecelano-test/git-commit-signature/issues/2)
- [Example 03: pull request with "rebase and merge"](https://github.com/josecelano-test/git-commit-signature/issues/4)

### Batch 03

Requirements:

- Committer and author are not the same.
- GPG key identity (user and email) is the same as the committer.
- No pull request. Push directly to the `main` branch.
- Author is: `Jose Celano <bot@josecelano.com>`.

Examples:

- [Example 04: committer and author are not the same](https://github.com/josecelano-test/git-commit-signature/issues/6)
