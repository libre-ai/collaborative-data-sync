<!-- SPDX-FileCopyrightText: 2026 Libre AI contributors -->
<!-- SPDX-License-Identifier: CC-BY-4.0 -->
<!-- Written for the retained Libre AI portfolio on 2026-09-14; earlier source documents and revisions retain their original licensing. -->

# Libre AI Collaborative Data Sync

## Usage visé

Fournir la frontière de synchronisation permettant aux applications d’échanger des modifications de documents entre clients. Elle porte sur la cohérence et le transport des changements ; l’application conserve leur sens métier et les autorités concernées décident des accès.

## Candidats existants et limites

Les anciennes sources comprennent un noyau de synchronisation, un relais et des interfaces de fournisseurs de test. Elles ne démontrent pas un parcours complet entre deux clients avec une cryptographie réelle et des appartenances autorisées. Ce candidat documentaire n’admet aucun relais opérationnel ou garantie de chiffrement de bout en bout.

## Contrats proposés

Un échange identifie son document, le contexte de révision et le résultat pertinent du protocole. La reconnexion précise le traitement des modifications absentes ou dupliquées. Le contrôle d’accès reste distinct du succès du transport : recevoir un message n’autorise pas à lire ou modifier le document. Protéger le contenu contre sa lecture par le relais est une exigence à qualifier, pas une propriété démontrée par un fournisseur d’identité de test.

## Critères d’activation

Qualifier un protocole exact et son consommateur avec deux clients réels, une appartenance explicite et l’implémentation cryptographique retenue. Tester les reconnexions, modifications concurrentes, doublons, accès révoqués et l’isolation entre documents et organisations. Observer ce que le relais peut lire et conserver avant d’affirmer la confidentialité. Les contrats canoniques nécessitent une admission par Contracts ; la synchronisation ne doit pas élargir silencieusement les permissions applicatives.

La qualification suit le périmètre réellement retenu. Un module candidat peut être admis séparément avec son consommateur et ses preuves ; les critères de parcours complet s’appliquent au produit ou à l’intégration correspondante. Un noyau pur ne nécessite pas une intégration de worker, de base de données ou de relais hors de son périmètre. Ni l’admission d’un module ni l’existence documentaire de ce dépôt ne nécessitent un parcours Missions complet.

[English](README.md)

## Navigation du portefeuille

Ces liens décrivent le portefeuille retenu visé. La disponibilité publique et l’accessibilité ne sont pas vérifiées pour ce candidat privé.

### Produits

- [Libre AI Work Supervision](https://github.com/libre-ai/ai-work-supervision)
- [Libre AI Model Policy](https://github.com/libre-ai/ai-model-policy)
- [Libre AI Practice Workbench](https://github.com/libre-ai/ai-practice-workbench)
- [Libre AI Learning Session Facilitation](https://github.com/libre-ai/learning-session-facilitation)
- [Libre AI Personal Knowledge Notebook](https://github.com/libre-ai/personal-knowledge-notebook)
- [Libre AI Information Feed Filter](https://github.com/libre-ai/information-feed-filter)
- [Libre AI Travel Itinerary Planner](https://github.com/libre-ai/travel-itinerary-planner)
- [Libre AI Public Vote Comparison](https://github.com/libre-ai/public-vote-comparison)

### Composants et outils

- [Libre AI Application Development Toolkit](https://github.com/libre-ai/application-development-toolkit)
- [Libre AI Schemas And Contracts](https://github.com/libre-ai/schemas-and-contracts)
- [Libre AI Collaborative Data Sync](https://github.com/libre-ai/collaborative-data-sync)
- [Libre AI Execution Continuity Evaluator](https://github.com/libre-ai/execution-continuity-evaluator)
- [Libre AI Execution Sandbox](https://github.com/libre-ai/execution-sandbox)
- [Libre AI Capability Authorization](https://github.com/libre-ai/capability-authorization)
- [Libre AI Organization Data Lifecycle](https://github.com/libre-ai/organization-data-lifecycle)
- [Libre AI Database Policy Inspector](https://github.com/libre-ai/database-policy-inspector)
- [Libre AI Artifact Verification](https://github.com/libre-ai/artifact-verification)

### Projet

- [Libre AI](https://github.com/libre-ai/.github)
- [Libre AI Project Website](https://github.com/libre-ai/project-website)
- [Libre AI Project Governance](https://github.com/libre-ai/project-governance)



---

## Source éditoriale revue

[Matière revue](https://github.com/libre-ai/collaborative-data-sync/blob/7d53442cad1fe9ed4ced8133bdd85867716a4b03/docs/portfolio-material.json)

SHA-256: `cde4f6c8fa91cb439be0991920675ab32219a3424c8cf4b738e6776418d8efee`
