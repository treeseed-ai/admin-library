---
schemaVersion: treeseed.knowledge-page/v2
id: vault.provider-credential-rotation
projectId: 4c520946-e4c3-460d-a50f-255b65c78451
bookRef:
  store: treedx
  model: book
  id: treeseed-credential-security
  path: books/credential-security.md
  revision: 1
  digest: sha256:e93c794a57eb4172e152306d2585a1ee2fd51f2d37e123f3eb7a277940849d24
slug: provider-credential-rotation
title: Rotating provider credentials
summary: Replace a token at its provider and then encrypt the replacement
  without confusing encryption rotation with credential revocation.
status: published
visibility: team
order: 40
groupIds:
  - compromise
  - credential
  - revoke
  - rotation
  - token
contributors: []
relatedBookIds: []
relatedKnowledgeIds:
  - services.credentials
  - vault.rotation
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
  - admin.services.vault
routePatterns:
  - /app/services/[connectionId]
  - /app/services/vault
resourceTypes:
  - credential-envelope
actionIds:
  - service.credential.replace
keywords:
  - credential
  - token
  - rotation
  - revoke
  - compromise
documentationUrls: []
---

If a provider credential may be exposed, revoke or rotate it in the provider’s own interface first. Re-encrypting the same value does not invalidate a copied token.

Create a replacement with the minimum required permissions, save it into the matching credential profile, validate it with a read-only lease, and then revoke the old provider credential.
