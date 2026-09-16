<!-- SPDX-FileCopyrightText: 2026 Libre AI contributors -->
<!-- SPDX-License-Identifier: CC-BY-4.0 -->
<!-- Written for the retained Libre AI portfolio on 2026-09-14; earlier source documents and revisions retain their original licensing. -->

# Libre AI Collaborative Data Sync

## Intended use

Provide the synchronization boundary that applications can use to exchange document changes between clients. It concerns the consistency and transport of changes, while the application keeps its product meaning and the relevant authorities decide access.

## Existing candidates and limits

Earlier sources contain a synchronization core, relay and test-provider boundaries. They do not establish a complete two-client journey with real cryptography and authorized membership. This documentary candidate admits no operating relay or end-to-end encryption guarantee.

## Proposed contracts

A change exchange identifies its document, revision context and relevant protocol outcome. Reconnection describes how missing or duplicate changes are handled. Access checks remain distinct from transport success: receiving a message does not grant permission to read or modify the document. Protecting document content from a relay is a requirement to qualify, not a property established by a test identity provider.

## Activation criteria

Qualify an exact protocol and consumer with two real clients, explicit membership and the selected cryptographic implementation. Test reconnection, concurrent edits, duplicates, revoked access and isolation between documents and organizations. Observe what the relay can read and retain before making confidentiality claims. Canonical contracts require admission by Contracts; synchronization must not silently expand application permissions.

Qualification follows the actual selected scope. A candidate module may be admitted independently with its own consumer and evidence; complete journey criteria apply to the corresponding product or integration. A pure core does not require a worker, database or relay integration that is outside its scope. Neither module admission nor this repository’s documentary existence requires a complete Missions journey.

[Français](README.fr.md)

## Portfolio navigation

These links describe the intended retained portfolio. Public availability and reachability are not verified for this private candidate.

### Products

- [Libre AI Work Supervision](https://github.com/libre-ai/ai-work-supervision)
- [Libre AI Model Policy](https://github.com/libre-ai/ai-model-policy)
- [Libre AI Practice Workbench](https://github.com/libre-ai/ai-practice-workbench)
- [Libre AI Learning Session Facilitation](https://github.com/libre-ai/learning-session-facilitation)
- [Libre AI Personal Knowledge Notebook](https://github.com/libre-ai/personal-knowledge-notebook)
- [Libre AI Information Feed Filter](https://github.com/libre-ai/information-feed-filter)
- [Libre AI Travel Itinerary Planner](https://github.com/libre-ai/travel-itinerary-planner)
- [Libre AI Public Vote Comparison](https://github.com/libre-ai/public-vote-comparison)

### Components and tools

- [Libre AI Application Development Toolkit](https://github.com/libre-ai/application-development-toolkit)
- [Libre AI Schemas And Contracts](https://github.com/libre-ai/schemas-and-contracts)
- [Libre AI Collaborative Data Sync](https://github.com/libre-ai/collaborative-data-sync)
- [Libre AI Execution Continuity Evaluator](https://github.com/libre-ai/execution-continuity-evaluator)
- [Libre AI Execution Sandbox](https://github.com/libre-ai/execution-sandbox)
- [Libre AI Capability Authorization](https://github.com/libre-ai/capability-authorization)
- [Libre AI Organization Data Lifecycle](https://github.com/libre-ai/organization-data-lifecycle)
- [Libre AI Database Policy Inspector](https://github.com/libre-ai/database-policy-inspector)
- [Libre AI Artifact Verification](https://github.com/libre-ai/artifact-verification)

### Project

- [Libre AI](https://github.com/libre-ai/.github)
- [Libre AI Project Website](https://github.com/libre-ai/project-website)
- [Libre AI Project Governance](https://github.com/libre-ai/project-governance)



---

## Reviewed editorial source

[Reviewed material](https://github.com/libre-ai/collaborative-data-sync/blob/7d53442cad1fe9ed4ced8133bdd85867716a4b03/docs/portfolio-material.json)

SHA-256: `cde4f6c8fa91cb439be0991920675ab32219a3424c8cf4b738e6776418d8efee`
