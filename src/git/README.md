# Git

This directory contains configuration files for [Git](https://git-scm.com/).

It is synced to `~/.config/git`[^1] and includes:

- `config`: The main configuration file for Git.
- `ignore`: A global `.gitignore` file for all repositories and languages.
- `attributes`: A global `.gitattributes` file for all repositories and languages.
- `signers`: A file specifying allowed signers for GPG signatures.

[^1]: NOTE: This assumes the environment variable `XDG_CONFIG_HOME` is set to `~/.config`. If not, the files will be synced to `~/.gitconfig`, `~/.gitignore`, etc.

***

Related:

- [ssh](../ssh/): SSH configuration for Git and other tools.
- [gpg](../gpg/): GPG configuration for signing commits and tags.
- [gh](../gh/): GitHub CLI configuration.
- [gitkraken](../gitkraken/): GitKraken configuration.
