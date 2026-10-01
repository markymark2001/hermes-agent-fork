# Employee model surface

- Status: active
- Scope: tool filter, skill loading and client visibility
- Introduced: employee surface audit; narrowed by user direction

## Downstream intent

Keep the approved model tools and configured MCP. Disable skills in agent
loading/invocation, curator and sync. Hide selected dashboard/TUI/desktop
controls while retaining native CLI, backend APIs and configuration semantics.
Model-facing instructions must not recommend disabled skills or the removed
`cronjob` tool. Route task knowledge to responsibilities/connection manuals and
automation to responsibility schedules. Adapt wording in native prompt owners;
do not add a post-processing layer or change warm-session prompts.

## Reconciliation

Do not widen model tools when restoring administration. Do not restore backend
rejections, fixed memory-provider selection, SOUL bans or native cron-authoring
bans merely because their client controls are hidden. Responsibility-owned jobs
retain their declaration ownership checks. Hindsight uses current-message recall
and exposes only `recall`; deployment selects it through native configuration.

## Validation

Exercise actual schemas, skill loading and native administrative endpoints.
Run owning Python and client tests. See the [scope ledger](../scope.md).
