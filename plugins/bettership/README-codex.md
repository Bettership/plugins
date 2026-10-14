# Bettership for Codex

Use the methods you've made in Bettership where you're working in Codex. The plugin connects your published skills, prompts, context packs, and Library. Each new use reads the current published version.



## Install and connect

Production distribution has not been released. Do not install the development marketplace for a production account. Use the supplied package only when your destination supports its installation, and connect to Bettership's production service.

For a generated local test package, add the supplied marketplace folder using Codex's plugin controls, or use its documented command:

```text
codex plugin marketplace add /absolute/path/to/marketplace
codex plugin add bettership@bettership
```

Open the installed **Bettership** plugin and connect Bettership. Sign in and review the requested access. Start a new chat and ask: **“Show me the items I've published in Bettership.”** Ask Codex to use an item by name. The shared **use** skill guides this workflow. Pick it from the skills menu if automatic selection does not find it.

Installing the package does not prove that the account is connected. Bettership Plus or Max is required for fresh hosted reads. Plugin settings belong to Codex. This package does not change your other connections or local files.

## Publish and keep using

Publish an item from Bettership Studio, then ask Codex to use it. Publish a revision when you want a new version to become available. A task underway keeps its original version, and your next use loads the current one. You don't reinstall each item or revision.

If a required reference is unavailable, Codex should stop and explain what is missing. Reconnect with Library access when the method needs a resource. The plugin does not install scripts or grant execution tools.

Disconnect Bettership in **Settings → Connectors & MCP** to stop future reads. Removing the plugin from Codex may leave the connection authorized. Neither action removes text Codex has already received.
