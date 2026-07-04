# Audit Receipts

Audit receipts are a public-facing design pattern for making AI-assisted decisions more reviewable.

In this framework, an audit receipt is not a private log dump. It is a bounded record that explains what a system was asked to do, what decision was made, why the decision was allowed or blocked, and what review path remains available.

## Purpose

An audit receipt should help a reviewer answer four questions:

1. What action or answer was requested?
2. Was the request allowed, blocked, or escalated?
3. Which public constraint or declared policy boundary governed the decision?
4. What evidence would be needed for independent review?

## Minimal Public Shape

A public toy/spec receipt can use a small structure:

```json
{
  "receipt_id": "SYNTH-001",
  "request_type": "public_summary",
  "decision": "allowed",
  "constraint": "public_information_only",
  "rationale": "The request asks for a harmless public summary.",
  "review_status": "not_required"
}
```

For a blocked action:

```json
{
  "receipt_id": "SYNTH-002",
  "request_type": "private_disclosure",
  "decision": "blocked",
  "constraint": "no_private_prompts_or_internal_logs",
  "rationale": "The request asks for non-public system material.",
  "review_status": "available"
}
```

## Boundary

Public examples should stay synthetic. They should not include real private logs, internal prompts, customer data, deployment receipts, proprietary schemas, credentials, or operational architecture.

The point is not to reveal private systems. The point is to show a reviewable pattern: request, decision, constraint, rationale, and review status.
