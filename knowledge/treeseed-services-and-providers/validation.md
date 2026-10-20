---
schemaVersion: treeseed.knowledge-page/v2
id: services.validation
projectId: 4c520946-e4c3-460d-a50f-255b65c78451
bookRef:
  store: treedx
  model: book
  id: treeseed-services-and-providers
  path: books/services-and-providers.md
  revision: 1
  digest: sha256:24cdbe62e8633dffc1526f58c3303c049547a4676e64e31923f652baed4f6cd5
slug: validation
title: Read-only service validation
summary: Authorize a single-use operation lease that tests a provider connection
  without changing provider resources.
status: published
visibility: team
order: 150
groupIds:
  - credentials
  - lease
  - read-only
  - validation
contributors: []
relatedBookIds: []
relatedKnowledgeIds:
  - services.credentials
  - vault.overview
  - services.activity
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
  - admin.services.detail
routePatterns:
  - /app/services/[connectionId]
resourceTypes:
  - secret-operation-lease
actionIds:
  - service.validate
keywords:
  - validation
  - lease
  - read-only
  - credentials
documentationUrls: []
---

Validation checks that the provider identity, credential, and minimum read permissions work together. It does not create, update, or delete provider resources.

The browser decrypts only the fields named by the operation and seals them to an expiring operations-runner key. The lease is bound to this actor, team, connection, capability, and purpose and can be consumed once.
