<a href="https://hostkeep.tech"><img src="https://hostkeep.tech/og.png?v=2" alt="Hostkeep: ask your machines what happened last night" width="100%"></a>

# Hostkeep

**Your AI assistant on your Windows machines, inside walls you draw.**

Hostkeep is an MCP server for small teams that run bots, automations and client servers on Windows machines and VMs. It lets an AI assistant (Claude, ChatGPT, Codex and other MCP clients) diagnose a failed job, collect logs and outputs, and run tasks you defined, without remote desktop and without handing it the keys.

- **Read-only by default.** The assistant only sees the project folders you name. Writing is switched on per project.
- **Tasks, not a shell.** It runs commands you defined in advance, with checked parameters.
- **Walled-off projects.** File access is pinned by a Windows worker so it can't be redirected outside a project.
- **Every action on the record.** Each tool call is written to a local, hash-chained activity log. File contents are never logged.
- **No Hostkeep cloud.** It runs as a standard Windows user, with no admin rights and no telemetry.

**Status:** private beta, working today. We set it up with each team personally while the one-click installer is finished.

[Website](https://hostkeep.tech) · [What it does and doesn't](https://hostkeep.tech/scope) · [Security model](https://hostkeep.tech/security) · [Join the private beta](https://hostkeep.tech/contact) · [@HostKeepHQ](https://x.com/HostKeepHQ)

Security reports: fay@hostkeep.tech (see [security.txt](https://hostkeep.tech/.well-known/security.txt)).
