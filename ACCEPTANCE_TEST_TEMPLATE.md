# AI Agent Acceptance Test Template

Use this before accepting Codex, Claude Code, Cursor, review-agent, browser-QA, or local-agent output as production-ready.

## Run Under Test

| Field | Value |
| --- | --- |
| Run ID |  |
| Project |  |
| Objective |  |
| Agent |  |
| Model |  |
| Output link |  |
| Files changed |  |
| Verifier |  |

## Acceptance Criteria

| Criterion | Pass Signal | Evidence |
| --- | --- | --- |
| Objective match | Output satisfies the original done condition |  |
| Scope match | Only allowed files or surfaces changed |  |
| Behavior proof | The changed behavior was tested directly |  |
| Regression check | Relevant existing behavior still passes |  |
| Security / privacy | No secret, auth, payment, or private data leak |  |
| Cost discipline | Model and retry cost match task risk |  |
| Handoff quality | Next action and known gaps are recorded |  |
| Revenue / delivery proof | Money claims use payment or delivery evidence only |  |

## Hold Conditions

Hold the run if:

- The done condition is not testable.
- The evidence does not cover the changed behavior.
- The diff touches out-of-scope files.
- A required command, URL, screenshot, release asset, or digest is missing.
- Payment, auth, legal, or delivery claims lack direct proof.
- The next reviewer cannot understand the current state without chat history.

## Buyer Request Packet

Use these exact lines when requesting the team license:

```text
Invoice request packet: Agent Ops Command Center
Request package: Team license - 7 seats - $203 gross
Need: AI-agent acceptance test templates for objective, scope, behavior, regression, security, cost, handoff, and revenue-proof gates.
Proof rule: Count revenue only after checkout, receipt, payout, or seller-dashboard evidence.
```

Primary $203 team request URL:

https://ivelly42.github.io/agent-ops-command-center/team-request-url.html

Checkout status:

https://ivelly42.github.io/agent-ops-command-center/checkout-status.json

Invoice request packet:

https://ivelly42.github.io/agent-ops-command-center/team-invoice-request.html

## Revenue Rule

Acceptance-test interest is not revenue.

Count revenue only when checkout, receipt, payout, or seller-dashboard evidence proves payment.
