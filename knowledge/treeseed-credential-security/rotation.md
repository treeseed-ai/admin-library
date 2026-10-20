---
schemaVersion: treeseed.knowledge-page/v2
id: vault.rotation
projectId: 4c520946-e4c3-460d-a50f-255b65c78451
bookRef:
  store: treedx
  model: book
  id: treeseed-credential-security
  path: books/credential-security.md
  revision: 1
  digest: sha256:e93c794a57eb4172e152306d2585a1ee2fd51f2d37e123f3eb7a277940849d24
slug: rotation
title: Passphrase, team-key, and provider credential rotation
summary: Choose the rotation that matches the material that may be exposed.
status: published
visibility: authenticated
order: 70
groupIds:
  - rotate-passphrase
  - rotate-team-key
  - rotate-token
contributors: []
relatedBookIds: []
relatedKnowledgeIds:
  - vault.grants
  - vault.recovery
  - services.credentials
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
  - rotate passphrase
  - rotate team key
  - rotate token
documentationUrls: []
---

Personal passphrase rotation re-encrypts only your administrator private-key envelope. Provider credentials do not need to be decrypted or rewritten.

Team vault-key rotation rewraps credential keys and remaining administrator grants. Use it after grant revocation or suspected team-key exposure.

Provider credential rotation happens at GitHub, Cloudflare, Railway, or the relevant provider. Re-encrypting a token does not invalidate a token that was already exposed.
