# Contributing Guide
If you intended to view this guide or had contributed in different way(s), I would like to thank you
for taking your time to contribute or cooperate on my project.

## How can I contribute?
You can contribute in different ways by:
- [Creating an issue](#creating-an-issue)
- [Resolving an issue](#resolving-an-issue)

### Creating an issue
This allows you to do one of the following:
- Request a feature
- Report a bug

It is recommended to be clear on reporting bugs or requesting feature.

### Resolving an issue
You may find issues that you can solve. If you want to add possible fixes for a certain issue, it is
recommended to follow the [initialization steps].

Following the initialization steps ensures that the format new commits in the repository adhere in
[Conventional Commits specification] and to the preferences of the maintainer. The commit types
allowed in the repository are on the [next section](#allowed-commit-types).

Ensure that your changes is consistent with the formatting of the other code or related files. This
will reduce friction when the maintainer read the changes. Majority of formatting for code and
different contents can be found in [`.editorconfig`].

### Allowed Commit Types
The commit types are dependent on the type of changes in the code. Commits should be atomic as much
as possible to not confuse the reviewers, easy to rebase or cherry-pick the commit, and generation of change logs.

Meanwhile, the scope names are dependent on the topic. It is recommended to looking on the previous
commits to see the pattern on scope names.
[Conventional Commits specification]: https://www.conventionalcommits.org/en/v1.0.0/
[initialization steps]: ./README.md#initialization
[`.editorconfig`]: ./.editorconfig
