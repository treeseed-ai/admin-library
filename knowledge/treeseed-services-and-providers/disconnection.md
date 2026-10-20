---
schemaVersion: treeseed.knowledge-page/v2
id: services.disconnection
projectId: 4c520946-e4c3-460d-a50f-255b65c78451
bookRef:
  store: treedx
  model: book
  id: treeseed-services-and-providers
  path: books/services-and-providers.md
  revision: 1
  digest: sha256:24cdbe62e8633dffc1526f58c3303c049547a4676e64e31923f652baed4f6cd5
slug: disconnection
title: Disconnecting a service
summary: Resolve capability consumers before removing a connection and its
  encrypted credential records.
status: published
visibility: team
order: 70
groupIds:
  - blocker
  - ciphertext
  - delete
  - disconnect
contributors: []
relatedBookIds: []
relatedKnowledgeIds:
  - services.settings
  - services.capabilities
  - vault.reset
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
  - team-service-connection
actionIds:
  - service.connection.disconnect
keywords:
  - disconnect
  - delete
  - blocker
  - ciphertext
documentationUrls: []
---

Disconnecting removes TreeSeed’s connection metadata, capability bindings, credential profiles, encrypted envelopes, and related run-owned leases. It does not delete anything at the provider.

The operation is blocked while another platform resource references the connection. Resolve every dependency before confirming disconnection.
