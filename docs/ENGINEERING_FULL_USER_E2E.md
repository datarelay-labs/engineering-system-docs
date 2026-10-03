# Engineering System Docs — Full User E2E

## Purpose

This is the mandatory depth-first real-user browser gate for the exact documentation candidate after Surface Reconciliation converges.

## Executor and surface

**ChatGPT itself is the executor and final auditor.** ChatGPT directly assumes realistic reader/operator personas and completes the missions through a real Chromium/Chrome browser. CI, curl/API probes, static MDX checks, scripted scenario replay, or another agent cannot substitute for the user action.

## Mandatory missions

At minimum execute complete browser journeys for:

1. First-time reader: landing page → understand the Engineering System purpose → reach quickstart/adoption guidance.
2. Active engineer: navigate workflow/session-continuity guidance → follow a relevant cross-link/reference → verify the guidance is actionable and current.
3. Search-driven reader: use browser search to locate a specific topic → open a result → continue to a second relevant page through visible navigation.
4. Bilingual/navigation continuity where published.
5. Failure/recovery: unknown route, empty/no-result search, Back/Forward/reload/deep-link behavior; recover without source knowledge.

## Execution semantics

Run mission-first and black-box. The acting persona starts without source/config answer-key knowledge and follows rendered navigation, search, and visible guidance.

A finding is not a stop condition. Preserve evidence and continue every safe independent mission. Freeze findings at pass end, batch-remediate, and rerun invalidated E2E from the beginning. If remediation changes public navigation or the surface contract, rerun Surface Reconciliation.

Use a clean deployed preview or public exact-candidate build and record candidate identity. Repeat reload/new-context/deep-link variants when one success could hide stale routing defects. Report environment/tooling blockage honestly; never convert it to PASS.

Retain machine-readable mission/findings ledgers and derive the summary from them. PASS requires 100% applicable mission/real-effect coverage, zero mandatory FAIL/PARTIAL/BLOCKED, zero unresolved blocking finding, and cleanup of run-owned browser/test state.

The final clean Full User E2E and Surface Reconciliation must bind to the **same exact HEAD**. Only after ChatGPT directly executes and finally audits both clean gates may the authoritative release Work Packet record terminal product-quality closure and freeze that exact HEAD as the candidate.
