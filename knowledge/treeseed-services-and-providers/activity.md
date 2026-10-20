---
schemaVersion: treeseed.knowledge-page/v2
id: services.activity
projectId: 4c520946-e4c3-460d-a50f-255b65c78451
bookRef:
  store: treedx
  model: book
  id: treeseed-services-and-providers
  path: books/services-and-providers.md
  revision: 1
  digest: sha256:24cdbe62e8633dffc1526f58c3303c049547a4676e64e31923f652baed4f6cd5
slug: activity
title: Service activity and validation history
summary: Review connection changes and validation outcomes without exposing
  credential values.
status: published
visibility: team
order: 10
groupIds:
  - activity
  - audit
  - timestamp
  - validation
contributors: []
relatedBookIds: []
relatedKnowledgeIds:
  - services.connection
  - services.validation
  - services.settings
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
  - service.activity.read
keywords:
  - activity
  - audit
  - validation
  - timestamp
documentationUrls: []
---

Service activity records security-sensitive metadata such as who connected or edited a provider, which capability changed, and whether read-only validation succeeded.

Times are displayed in your account time zone. Audit payloads contain fingerprints and correlation identifiers, never passphrases, plaintext credentials, derived keys, or decrypted provider responses.
