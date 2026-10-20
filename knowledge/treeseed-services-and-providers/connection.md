---
schemaVersion: treeseed.knowledge-page/v2
id: services.connection
projectId: 4c520946-e4c3-460d-a50f-255b65c78451
bookRef:
  store: treedx
  model: book
  id: treeseed-services-and-providers
  path: books/services-and-providers.md
  revision: 1
  digest: sha256:24cdbe62e8633dffc1526f58c3303c049547a4676e64e31923f652baed4f6cd5
slug: connection
title: Service connection administration
summary: Maintain metadata, capabilities, credential readiness, activity,
  validation, and safe disconnection.
status: published
visibility: authenticated
order: 40
groupIds:
  - capabilities
  - connection-settings
  - disconnect
  - validation
contributors: []
relatedBookIds: []
relatedKnowledgeIds:
  - services.credentials
  - services.external-vault
  - services.providers
  - services.connections
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
actionIds: []
keywords:
  - connection settings
  - capabilities
  - validation
  - disconnect
documentationUrls: []
---

The connection page separates readable provider metadata from encrypted credential custody.

Changing capabilities does not automatically create provider resources. It records which provider-neutral capability bindings future operations may select.

Read-only validation uses an operation-scoped lease and only the credential fields required by that validation. Disconnection is blocked while another allocation depends on the connection and permanently removes its encrypted credential envelopes when it succeeds.
