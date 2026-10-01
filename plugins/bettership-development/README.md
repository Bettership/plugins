# Bettership for Claude

Use your Bettership Library, skills, prompts, and context packs in Claude. Install once, then publish items from Bettership Studio whenever you want to use them.

**Development release:** this plugin connects to Bettership’s development service. Use your Bettership development account; production accounts and items are separate.

## Set up Claude

1. Open [Claude’s Plugins page](https://claude.ai/customize/plugins). Choose **Add → Add marketplace**, paste `https://github.com/Bettership/plugins`, turn off **Sync automatically**, and select **Sync**. Add **Bettership development** from the results.
2. Open the plugin’s **Connectors** tab. Select **Add** if shown, then **Connect**. Sign in to Bettership and choose what Claude can access.
3. Start a new conversation and ask: **“Show me the items I’ve published in Bettership.”** Ask Claude to use an item by name.

Requires a Claude plan with plugins and Bettership Pro or Max. If your work account blocks setup, ask its owner to allow the plugin and add its connector.

## Publish and update

In Bettership Studio, open an item and publish it to your AI tools. Enable **Publish updates automatically** to make future completed revisions available too. Claude gets the current published version the next time you use it. A task already underway keeps the version it started with.

Your items stay in Bettership. You do not need to download or reinstall them. Published items stay up to date without marketplace auto-sync or GitHub App access. Automatic publishing does not make Maker create revisions on a schedule.

## Cowork and Claude Code

The plugin is also available in Cowork and supported Claude Code versions when you sign in with the same Claude account. Start a new session after installation. Connect Bettership if prompted.

For a direct installation in Claude Code 2.1.275 or later, paste:

```text
/plugin install bettership-development --marketplace Bettership/plugins
```

Then open `/mcp` and sign in to Bettership. Use `/bettership-development:use` to get started. Direct Claude Code installation does not install the plugin in Claude chat.

## If something is missing

- **No items:** publish an item in Bettership Studio, then ask again in a new conversation.
- **An item needs a Library resource:** reconnect Bettership with Library access if you want Claude to read it.
- **Asked to sign in again:** reconnect from Claude’s Connectors page or `/mcp` in Claude Code.

The plugin supplies instructions and a connection. It does not install scripts that a Maker item needs or give Claude tools it does not have. Disconnecting stops future access; it cannot remove text already received by Claude.
