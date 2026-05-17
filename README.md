# observo-ai-plugins

Claude Code plugin marketplace maintained by [Observo](https://observoai.co).

## Install

Inside Claude Code, run:

```
/plugin marketplace add observo-ai/claude-plugins
```

Then install any plugin from the catalog:

```
/plugin install <plugin-name>@observo-ai-plugins
```

## Plugins in this catalog

| Plugin | What it does |
|---|---|
| [`observo-qa-toolkit`](https://github.com/observo-ai/observo-qa-toolkit) | QA + product spec toolkit. 7 skills covering `prd` → `requirements-testing` → `observo-test-cases` → `observo-code-verifier` → `observo-review-test-case` → `pw-generate` → `pw-run`. Repo-agnostic; works on any Playwright project. |

## How updates work

Each plugin in this marketplace pins a `branch` (or, when stable, a tagged version). After upstream releases a new version, the corresponding entry in [`marketplace.json`](.claude-plugin/marketplace.json) is updated and committed; users running `/plugin update` then pick up the new version.

## Contributing

This catalog is curated by Observo. Bug reports and feature requests for individual plugins go to the plugin's own repository (linked in the table above). Marketplace-level issues (manifest validation, install instructions) belong here.

## License

MIT — see [LICENSE](LICENSE).
