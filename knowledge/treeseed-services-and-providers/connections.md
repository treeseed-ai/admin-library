---
schemaVersion: treeseed.knowledge-page/v2
id: services.connections
projectId: 4c520946-e4c3-460d-a50f-255b65c78451
bookRef:
  store: treedx
  model: book
  id: treeseed-services-and-providers
  path: books/services-and-providers.md
  revision: 1
  digest: sha256:24cdbe62e8633dffc1526f58c3303c049547a4676e64e31923f652baed4f6cd5
slug: connections
title: Connected provider services
summary: Understand provider connections, capability bindings, custody
  readiness, and active-team scope.
status: published
visibility: authenticated
order: 50
groupIds:
  - active-team
  - capabilities
  - connections
  - providers
  - services
contributors: []
relatedBookIds: []
relatedKnowledgeIds:
  - services.connect
  - services.connection
  - services.credentials
  - services.providers
  - vault.overview
relatedNoteIds: []
relatedQuestionIds: []
relatedObjectiveIds: []
relatedProposalIds: []
relatedDecisionIds: []
guaranteeIds: []
audiences:
  primary: []
  secondary: []
  excluded: []
capabilityIds:
  - admin.services.collection
routePatterns:
  - /app/services
resourceTypes:
  - team-service-connection
actionIds: []
keywords:
  - services
  - providers
  - connections
  - capabilities
  - active team
documentationUrls: []
---

A service connection represents a provider account boundary such as a GitHub organization, Cloudflare account, or Railway workspace.

Connections belong to the active team. Switching teams immediately changes the collection and never exposes another team’s encrypted envelopes.

Capabilities are enabled independently. A provider may support repository hosting, workflow execution, secret enclaves, frontend hosting, or other purposes without making those purposes interchangeable.
