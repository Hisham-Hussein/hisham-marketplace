# hisham-marketplace

The catalogue of Hisham's Claude Code plugins. Each plugin lives in its own repo; this repo
only lists them in `.claude-plugin/marketplace.json`.

| Plugin | Repo |
|---|---|
| claude-forge | [Hisham-Hussein/claude-forge](https://github.com/Hisham-Hussein/claude-forge) |
| content-generation | [Hisham-Hussein/content-generation](https://github.com/Hisham-Hussein/content-generation) |
| ambition | [Hisham-Hussein/ambition](https://github.com/Hisham-Hussein/ambition) |

## Install

```bash
claude plugin marketplace add Hisham-Hussein/hisham-marketplace
claude plugin install claude-forge@hisham-marketplace
claude plugin install content-generation@hisham-marketplace
claude plugin install ambition@hisham-marketplace
```

## Adding a plugin

Add an entry with a `github` source to `.claude-plugin/marketplace.json`, run
`claude plugin validate .`, commit and push, then `claude plugin marketplace update hisham-marketplace`.
