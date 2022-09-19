# 📄 GitHub Repo Files Sync

For Common GitHub files across my repositories.

This repository contains common configuration files/GitHub Action workflows I use across my repositories.

Using the [action-github-file-sync](https://github.com/BetaHuhn/action-github-file-sync) Action the files/workflows are automatically kept in sync. It runs on every push and creates a PR in my other repositories if a file was changed.

## `GH_PAT` for `BetaHuhn/repo-file-sync-action`

Below are the permissions needed for the `BetaHuhn/repo-file-sync-action`:

| Permission | Reason                                                                                                                                                                           |
|:----------:|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|   `repo`   | Required to create/modify PRs (see [BetaHuhn/repo-file-sync-action#31](https://github.com/BetaHuhn/repo-file-sync-action/discussions/31#discussioncomment-674804) for details).  |
| `workflow` | Required to create or update workflow files.                                                                                                                                     |