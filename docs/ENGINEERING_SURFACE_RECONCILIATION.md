# Engineering System Docs — Surface Reconciliation

## Purpose

This is the mandatory breadth-first browser gate for the exact documentation candidate. It proves that every supported documentation capability and visible browser surface is discoverable, coherent, usable, and free of blocking navigation, terminology, and rendering defects.

## Executor

**ChatGPT itself is the executor and final auditor.** ChatGPT acts as a real reader/operator persona and directly drives a real Chromium/Chrome browser against the deployed preview or public site for the exact candidate. Coding agents, alternate models, scripted replays, CI, API-only checks, static Markdown/MDX inspection, and component tests are supporting evidence only and cannot produce gate PASS.

## Black-box-first reconciliation

Start from the documented user capabilities and real browser entry point, not source/routes/config internals. The acting persona discovers navigation, search, language selection, guides, examples, cross-links, error/empty states, and next actions through the rendered site. Only after public evidence is frozen may the auditor inspect docs.json/MDX/source/config to detect hidden, stale, duplicate, orphaned, or undiscoverable surfaces.

## Mandatory coverage

Reconcile all applicable landing/navigation, published language paths, search/deep links, workflow/reference guides, canonical source links, code/example/diagram rendering, responsive layout, 404/empty-search recovery, terminology/procedure consistency, dead ends, broken assets, and misleading current-state claims.

Every mandatory capability/control receives an explicit PASS/FAIL/PARTIAL/BLOCKED/NOT_APPLICABLE disposition.

## Finding loop and evidence

A finding is not a stop condition. Record it and continue every safe independent page/journey. Do not patch source or this contract during the frozen discovery pass. After safe coverage is exhausted, freeze the complete finding set, batch-remediate, and rerun from the beginning on the new candidate.

Retain exact candidate HEAD, committed contract digest, browser/version, tested URLs, capability/page/navigation ledgers, findings ledger, screenshots when useful, and a ledger-derived summary. Release PASS requires 100% applicable capability/public-surface coverage, zero mandatory FAIL/PARTIAL/BLOCKED, and zero unresolved blocking finding.
