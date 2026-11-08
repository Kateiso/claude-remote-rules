# Claude remote routing rules

This rule source routes Claude traffic through the selected `PROXY` policy.
Set each client’s `PROXY` policy to a Canada node or Canada proxy group.

Files:

- `claude.list` — Shadowrocket and DoggyGo remote rule source.
- `claude.yaml` — Clash/Mihomo rule-provider payload.

Domains:

- `claude.ai`
- `bridge.claudeusercontent.com`

The rule source does not select a node by itself. Node selection remains a client policy choice.
