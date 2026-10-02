# Security and plugin review

Plugins can run commands, read or modify project files, manage servers, and use external services. Review each plugin's instructions and source before enabling it.

- Use an isolated worktree or disposable project.
- Start with non-sensitive data.
- Check server startup and cleanup behavior.
- Review shell commands, network calls, credentials, and file changes.
- Inspect generated test artifacts and diffs before keeping them.

Marketplace inclusion is not a security review or guarantee. Report vulnerabilities privately through GitHub if enabled or contact the plugin maintainer using a verified channel. Do not publish secrets or exploit details.
