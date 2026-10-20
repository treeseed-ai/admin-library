---
schemaVersion: treeseed.knowledge-page/v2
id: vault.reset
projectId: 4c520946-e4c3-460d-a50f-255b65c78451
bookRef:
  store: treedx
  model: book
  id: treeseed-credential-security
  path: books/credential-security.md
  revision: 1
  digest: sha256:e93c794a57eb4172e152306d2585a1ee2fd51f2d37e123f3eb7a277940849d24
slug: reset
title: Destructive vault reset
summary: Permanently discard inaccessible encrypted credentials and initialize
  replacement custody.
status: published
visibility: authenticated
order: 60
groupIds:
  - discard-credentials
  - irreversible
  - reauthentication
  - reset-vault
contributors: []
relatedBookIds: []
relatedKnowledgeIds:
  - vault.recovery
  - vault.grants
  - vault.rotation
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
  - admin.services.vault
routePatterns:
  - /app/services/vault
resourceTypes:
  - team-vault
actionIds: []
keywords:
  - reset vault
  - discard credentials
  - irreversible
  - reauthentication
documentationUrls: []
---

Reset is only for the case where no usable administrator grant remains.

The operation permanently discards protected provider credential envelopes. It cannot recover, reveal, or migrate their plaintext values. Every credential must be recreated or reentered afterward.

Reset requires owner authorization, recent account reauthentication, your personal vault passphrase for the replacement grant, and the exact confirmation text shown by the form.
