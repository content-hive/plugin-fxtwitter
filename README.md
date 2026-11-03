# Content Hive Plugin: X(Twitter)

An X(Twitter) content parsing plugin for Content Hive. Parses Twitter/X.com status URLs to extract post content, images, videos, and author information via the fxtwitter API.

Plugin for [Content Hive](https://github.com/content-hive/content-hive).

## Layout

```
plugin/              # plugin source, installed as plugins/fxtwitter/ by Content Hive
├── manifest.json    # plugin metadata (domain, version, requirements, release_notes)
├── __init__.py
└── ...
contenthive.json     # repository metadata for the Content Hive plugin catalog
```

## Releasing

1. Bump `version` and rewrite `release_notes` in `plugin/manifest.json`.
2. Merge into `main`.
3. Publish a GitHub Release whose tag is `v<version>` (for example `v0.1.8`).
