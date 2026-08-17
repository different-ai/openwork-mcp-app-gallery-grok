# Hosted MCP Apps Example Gallery (grok)

This repository is an **independent hosted adaptation** of selected official
[MCP Apps](https://github.com/modelcontextprotocol/ext-apps) examples. It is
**not** an official Model Context Protocol service, product, or endorsement.

The intended user outcome is: copy one remote Streamable HTTP MCP URL, add it
to an MCP Apps-compatible host, and try the example without cloning upstream
or opening a tunnel.

## Current status

Repository governance is in place. The six-app catalog, MCP endpoints, gallery
page, and production URLs are implemented on the `grok/gallery-v1` feature
branch and published only after verification. This file is updated when those
endpoints exist.

## Source freeze

Upstream examples are pinned to
[`modelcontextprotocol/ext-apps@10195ad91851502134930e9b80ec2c04e277a720`](https://github.com/modelcontextprotocol/ext-apps/commit/10195ad91851502134930e9b80ec2c04e277a720).
Production builds never fetch upstream `main`.

See `THIRD_PARTY_NOTICES.md` and `upstream/manifest.json` after example source
is imported.

## License

Gallery-owned code is licensed under Apache-2.0. Copied upstream example files
retain the licenses recorded in `THIRD_PARTY_NOTICES.md`.
