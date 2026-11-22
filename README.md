# Basic 50 — Cojudge plugin

A [Cojudge](https://github.com/cojudge/cojudge) problem pack: 50 original
introductory problems that bridge the gap before Blind 75. It covers if/else,
loops, arrays, strings, nested loops and recursion with small, friendly tasks.

## Install

```bash
cojudge plugin install basic-50          # from the catalog
cojudge plugin install cojudge/basic-50  # or straight from GitHub
```

Or open the **Plugins** page in the Cojudge web UI. Once installed, the pack
works offline.

## Layout

```
cojudge-plugin.json       plugin manifest
courses/basic50/          course definition
problems/<slug>/          statement.md, metadata.json, official-tests.json, Marker.java, solution.md
```

`"unprefixedIds": true` keeps the bare problem ids these problems had when
they were bundled with Cojudge, so existing progress still matches. See
Cojudge's [`docs/PLUGINS.md`](https://github.com/cojudge/cojudge/blob/main/docs/PLUGINS.md).

## License

MIT
