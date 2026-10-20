---
schemaVersion: treeseed.knowledge-page/v2
id: services.settings
projectId: 4c520946-e4c3-460d-a50f-255b65c78451
bookRef:
  store: treedx
  model: book
  id: treeseed-services-and-providers
  path: books/services-and-providers.md
  revision: 1
  digest: sha256:24cdbe62e8633dffc1526f58c3303c049547a4676e64e31923f652baed4f6cd5
slug: settings
title: Service connection settings
summary: Change readable account metadata and enabled capabilities without
  exposing or replacing encrypted credentials.
status: published
visibility: team
order: 140
groupIds:
  - account-id
  - metadata
  - organization
  - settings
  - workspace
contributors: []
relatedBookIds: []
relatedKnowledgeIds:
  - services.connection
  - services.capabilities
  - services.disconnection
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
  - service.connection.update
keywords:
  - settings
  - metadata
  - account id
  - workspace
  - organization
documentationUrls: []
---

Connection settings contain non-secret identifiers and labels administrators need to recognize and route the provider account. They are stored as searchable metadata.

Credential profiles are managed separately. Updating a connection name, organization, account ID, or workspace ID never decrypts a credential envelope.
