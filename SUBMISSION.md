# Public marketplace submissions

Canonical source: https://github.com/buidly/refyner-claude
Install: `/plugin marketplace add buidly/refyner-claude` → `/plugin install refyner@refyner`

> Details below come from a verified research pass (2026-07-24), triangulated
> against the live Claude Code docs + GitHub API. Re-confirm URLs immediately
> before submitting. Nothing has been submitted. Submission happens only after
> owner approval, and outward-facing steps (forms/PRs) are done by the owner or
> with explicit go-ahead.

## Shortlist (ranked, verified)

### 1. Anthropic official community directory — SUBMIT FIRST
- **Repo:** `anthropics/claude-plugins-community` (installed as `@claude-community`).
  The repo is a read-only nightly-synced mirror — **do NOT open a PR** (auto-closed).
- **Submission method:** in-app/web **FORM** — `platform.claude.com/plugins/submit`
  (individual authors; short link `clau.de/plugin-directory-submission`), or
  `claude.ai/admin-settings/directory/submissions/plugins/new` for Team/Enterprise orgs.
- **Review:** runs `claude plugin validate` + automated safety screening (~days),
  then approved plugins sync nightly into the public `marketplace.json`.
- **Why first:** real Anthropic-run registry, surfaced in Claude Code's native
  `/plugin` UI; the highest-trust, highest-discovery path. Requires the owner's
  Anthropic account to submit the form.

### 2. composio-community/awesome-claude-plugins — SUBMIT (secondary)
- **Repo:** `composio-community/awesome-claude-plugins` (org-backed, ~1.8k★, active).
- **Submission method:** PR — fork → add plugin entry/folder → update README →
  open PR (per its CONTRIBUTING). Can be prepared as a ready branch.
- **Why:** legit, active, PR-based secondary listing for extra discoverability.

### 3. anthropics/claude-plugins-official — REVISIT LATER (not submittable now)
- Anthropic-**curated** (32k★); no application process — hand-picked, often after
  a plugin gains traction in `claude-plugins-community`. Not a direct target;
  revisit once `refyner` has usage.

### Optional / low priority
- `ananddtyagi/cc-marketplace` — real, PR-based, but small/low-traffic. Optional.
- `jimmc414/claude-code-plugin-marketplace` — new, ~4★. Very low reach. Optional.

### Skip (not marketplaces)
- `davila7/claude-code-templates`, `hesreallyhim/awesome-claude-code` — catalogs /
  awesome-lists, no `.claude-plugin/marketplace.json`; not `/plugin`-installable
  (a link/issue submission is possible but not a marketplace listing).

### Security note
A documented mid-2026 supply-chain attack via malicious marketplace plugins
means users increasingly prefer the **screened official path** — another reason
to lead with `claude-plugins-community`.

## Status

| Marketplace | Target | Submission method | Who submits | Status |
|---|---|---|---|---|
| Anthropic community directory | anthropics/claude-plugins-community | FORM (platform.claude.com/plugins/submit) | owner (Anthropic account) | not submitted |
| composio awesome-claude-plugins | composio-community/awesome-claude-plugins | PR | prep branch → owner opens PR | not submitted |
| Anthropic official (curated) | anthropics/claude-plugins-official | none (curated) | — | revisit after traction |
| cc-marketplace (optional) | ananddtyagi/cc-marketplace | PR | optional | not submitted |
| jimmc414 (optional) | jimmc414/claude-code-plugin-marketplace | PR | optional | not submitted |
