---
schemaVersion: treeseed.knowledge-page/v2
id: services.credentials
projectId: 4c520946-e4c3-460d-a50f-255b65c78451
bookRef:
  store: treedx
  model: book
  id: treeseed-services-and-providers
  path: books/services-and-providers.md
  revision: 1
  digest: sha256:24cdbe62e8633dffc1526f58c3303c049547a4676e64e31923f652baed4f6cd5
slug: credentials
title: Encrypted provider credentials
summary: Learn what is encrypted, who can use it, and how interactive operations
  receive credentials.
status: published
visibility: authenticated
order: 60
groupIds:
  - credentials
  - encryption
  - envelope
  - lease
  - token
contributors: []
relatedBookIds: []
relatedKnowledgeIds:
  - vault.overview
  - vault.grants
  - vault.rotation
  - services.external-vault
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
  - admin.services.vault
routePatterns:
  - /app/services/[connectionId]
  - /app/services/vault
resourceTypes:
  - credential-profile
actionIds: []
keywords:
  - credentials
  - encryption
  - token
  - envelope
  - lease
documentationUrls: []
---

Only authentication secrets are encrypted. Searchable account identifiers and labels remain ordinary metadata.

The browser encrypts each sensitive value with associated data binding it to the team, connection, profile, field, purpose, and envelope version. Moving ciphertext to another context makes it unusable.

For an interactive operation, the browser decrypts only required fields and seals them to a short-lived runner key. The runner consumes the lease once, uses plaintext in memory, redacts output, and discards the key material.
