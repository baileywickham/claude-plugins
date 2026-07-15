# claude-plugins

A [Claude Code plugin marketplace](https://code.claude.com/docs/en/plugin-marketplaces)
for my tools. Each plugin is a skill that teaches Claude to drive a CLI; the plugins
are fetched straight from their own repos, so they're always current with the code
they document.

## Install

```
/plugin marketplace add baileywickham/claude-plugins
/plugin install unifi-cli@baileywickham
```

## Plugins

| Plugin | What it does |
| --- | --- |
| [anki](https://github.com/baileywickham/anki-decks) | Create and edit Anki flashcards as version-controlled YAML, pushed into live Anki via AnkiConnect and synced everywhere through AnkiWeb. |
| [unifi-cli](https://github.com/baileywickham/unifi-cli) | Answer questions about your UniFi network — gateway, APs, connected clients — via the gateway's local Integrations API. |
| [ibkr](https://github.com/baileywickham/ibkr) | Research and trade options and stocks on Interactive Brokers — chains, quotes, Greeks, limit orders — with a preview/confirm/execute safety protocol. |

More coming.

## License

Each plugin carries its own license (see its repo). This catalog is MIT.
