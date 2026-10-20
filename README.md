# Bettership for Claude

Bettership is a personal AI workspace for ambitious professionals leveling up with online learning. This plugin brings what you're learning into Claude. Ask about the courses, podcasts, articles, books and notes in your Bettership Library, and use the prompts, context packs and skills you've made from them without copying or installing files. Install once, then publish items from Bettership Studio whenever you want to use them.



## Set up Claude

1. Open [Claude’s Plugins page](https://claude.ai/customize/plugins). Choose **Add → Add marketplace**, paste `https://github.com/Bettership/plugins`, turn off **Sync automatically**, and select **Sync**. Add **Bettership** from the results.
2. Open the plugin’s **Connectors** tab. Select **Add** if shown, then **Connect**. Sign in to Bettership and choose what Claude can access.
3. Start a new conversation and ask: **“Show me the items I’ve published in Bettership.”** Ask Claude to use an item by name.

Requires a Claude plan with plugins and Bettership Plus or Max. If your work account blocks setup, ask its owner to allow the plugin and add its connector.

## Publish and update

In Bettership Studio, open an item and publish it to your AI tools. Enable **Publish updates automatically** to make future completed revisions available too. Claude gets the current published version the next time you use it. A task already underway keeps the version it started with.

Your items stay in Bettership. You do not need to download or reinstall them. Published items stay up to date without marketplace auto-sync or GitHub App access. Automatic publishing does not make Maker create revisions on a schedule.

## Cowork and Claude Code

The plugin is also available in Cowork and supported Claude Code versions when you sign in with the same Claude account. Start a new session after installation. Connect Bettership if prompted.

For a direct installation in Claude Code 2.1.275 or later, paste:

```text
/plugin install bettership --marketplace Bettership/plugins
```

Then open `/mcp` and sign in to Bettership. Use `/bettership:use` to get started. Direct Claude Code installation does not install the plugin in Claude chat.

## If something is missing

- **No items:** publish an item in Bettership Studio, then ask again in a new conversation.
- **An item needs a Library resource:** reconnect Bettership with Library access if you want Claude to read it.
- **Asked to sign in again:** reconnect from Claude’s Connectors page or `/mcp` in Claude Code.

## What this plugin contains and connects to

The plugin has two parts: one skill that tells Claude how to use Bettership, and a connection to Bettership's service at `https://api.bettership.ai/mcp`. It runs no scripts, installs nothing else, and does not give Claude tools it does not already have, including any a Maker item may call for.

When you connect, Bettership asks you to sign in and shows what Claude is asking to read: your Library, your published items, or both. Claude can read what you allow and nothing more. It cannot add, change or delete anything in Bettership. Your practice history, your conversations with your Bettership agents and your learner profile stay in Bettership. Disconnecting stops future access. It cannot remove text Claude has already received.

## Help and privacy

- Setup guide: [Use what you made in your AI tools](https://docs.bettership.ai/apply/use-what-you-made-in-your-ai-tools)
- Support: [support@bettership.ai](mailto:support@bettership.ai)
- Privacy policy: [bettership.ai/privacy](https://www.bettership.ai/privacy)
- Terms of service: [bettership.ai/terms](https://www.bettership.ai/terms)
- License: MIT, in [LICENSE](LICENSE)
