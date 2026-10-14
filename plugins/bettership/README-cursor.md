# Bettership for Cursor

Bring a method you've made in Bettership into your work in Cursor. The plugin connects your published skills, prompts, context packs, and Library. Each new use reads the current published version.



## Install and connect

Production distribution has not been released. Do not install the development marketplace for a production account. Use the supplied package only when your destination supports its installation, and connect to Bettership's production service.

For development testing, copy this plugin folder under `~/.cursor/plugins/local/bettership`, then run **Developer: Reload Window**. Open **Customize** and confirm that the **use** skill and Bettership connection appear. Local imports must be allowed by your account's policy. Preserve an existing folder with this name instead of replacing its files. A marketplace installation with the same name takes precedence over a local copy.

An account marketplace can be imported under **Customize → Plugins → Add → From Local Repository**. Import a committed Git checkout of the supplied marketplace folder, then add **Bettership** for yourself. In Cursor 3.22.12, importing a generated folder without a commit displayed the plugin but failed to resolve `HEAD`. Adding a commit and reinstalling recovered the local connection. The earlier error disappeared after sign-in, when the connection displayed eight enabled tools and hosted reads succeeded. This route has not proved Grok Bot's cloud setup.

Connect **Bettership**, sign in to Bettership, and review the requested access. Start a new chat and ask: **“Show me the items I've published in Bettership.”** Ask Cursor to use an item by name. Pick the shared **use** skill when you want to invoke it directly.

Installing the package does not prove that the account is connected. Bettership Plus or Max is required for fresh hosted reads. This package does not change other connections, project rules, or learner-edited files.

## Publish and keep using

Publish an item from Bettership Studio, then ask Cursor to use it. Publish a revision when you want a new version to become available. A task underway keeps its original version, and your next use loads the current one. You don't reinstall each item or revision.

If a required reference is unavailable, Cursor should stop and explain what is missing. Reconnect with Library access when the method needs a resource. The plugin does not install scripts or grant execution tools.

Disconnect Bettership in **Settings → Connectors & MCP** to stop future reads. Removing the plugin from Cursor may leave the connection authorized. Neither action removes text Cursor has already received. Grok Bot's cloud computer needs separate setup and verification.
