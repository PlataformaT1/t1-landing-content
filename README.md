# t1-landing-content

Marketer-authored landing copy, written EXCLUSIVELY by the `landing-content-git-writer` GitHub App
through the frozen `landing.content-store-write-port` (SL-3) on Phoenix control-plane-ir
(PRJ-052; see Phoenix `libs/platform/l3-contract-content-store/co-design-write.md`).

- Content is append-only: versioned refs `<key>@vN` per locale; published refs are immutable.
- Do NOT edit this repo by hand — the write path is RBAC-gated + audited in Mission Control.
- Branch protection on `main`: only the content App may push; force-push and deletion forbidden.
