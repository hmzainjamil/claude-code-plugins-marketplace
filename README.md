# Claude Code Plugins Marketplace

This repository contains a Claude Code marketplace manifest with two plugin entries: [Interactive Architecture Agent](plugins/interactive-architecture-agent/README.md) and [Web App Testing Agent](plugins/web-app-testing-agent/README.md). Their metadata and instructions are maintained separately; inspect each plugin before enabling it.

## Marketplace files

| Path | Purpose |
|---|---|
| [.claude-plugin/marketplace.json](.claude-plugin/marketplace.json) | Marketplace owner and plugin source paths |
| [plugins/interactive-architecture-agent/.claude-plugin/plugin.json](plugins/interactive-architecture-agent/.claude-plugin/plugin.json) | Architecture plugin metadata |
| [plugins/web-app-testing-agent/.claude-plugin/plugin.json](plugins/web-app-testing-agent/.claude-plugin/plugin.json) | Web testing plugin metadata |
| [LICENSE](LICENSE) | Root MIT license |
| [Plugin template README](templates/plugin-template/README.md) | Template documentation, separate from the two marketplace entries |

Use Claude Code's current plugin documentation to add and use this marketplace. Review the selected plugin's full instructions, scripts, permissions, prerequisites, and effects first. Do not assume that listing a plugin means it has been tested or is safe for every project.

## Attribution and status

The marketplace manifest names `ingpoc` as owner, while this repository is under `hmzainjamil`. Plugin metadata also contains a placeholder email address. This README does not resolve ownership, transfer, synchronization, or endorsement. Confirm provenance with the relevant maintainers before redistribution or publishing.

The previous README's APIs, configuration, test coverage, benchmarks, case studies, and operational claims are removed because they were not supported by marketplace files. See [CONTENT_REVIEW.md](CONTENT_REVIEW.md).

## Security

Plugins may read and modify project files, start servers, run tests, and contact external services. Review permissions and use an isolated worktree with non-sensitive data first. See [SECURITY.md](SECURITY.md).
