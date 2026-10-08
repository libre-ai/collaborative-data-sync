# Collaborative Data Sync Agent Rules

## Authority

Collaboration core and relay, couche 4 brick of the Libre AI constellation.
Doctrine lives upstream:
https://raw.githubusercontent.com/libre-ai/project-governance/HEAD/AGENTS.md

## Boundaries

- Contract shapes are canonical in `libre-ai/schemas-and-contracts`, never
  redefined here; a new canonical contract is admitted there first.
- Synchronization never widens application permissions; access decisions
  stay with the consuming application.
- Product code and product specifications live in their own repositories;
  `packages/core` and `packages/relay` keep their own names and versions.

## Quality gates

Install through the shared local composition (`docs/development.md`), then
run `bun run check`. Never hide a red test.

## Agents

- Read actual state before editing.
- Stage files before running tree-walking gates.
- Security > quality > performance > completeness.
