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
| [unifi-cli](https://github.com/baileywickham/unifi-cli) | Answer questions about your UniFi network — gateway, APs, connected clients — via the gateway's local Integrations API. |

More coming.

## License

Each plugin carries its own license (see its repo). This catalog is MIT.
