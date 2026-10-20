---
schemaVersion: treeseed.knowledge-page/v2
id: vault.overview
projectId: 4c520946-e4c3-460d-a50f-255b65c78451
bookRef:
  store: treedx
  model: book
  id: treeseed-credential-security
  path: books/credential-security.md
  revision: 1
  digest: sha256:e93c794a57eb4172e152306d2585a1ee2fd51f2d37e123f3eb7a277940849d24
slug: overview
title: How the service vault works
summary: Understand personal keys, team custody, encrypted credentials, and the
  boundary TreeSeed cannot cross.
status: published
visibility: authenticated
order: 20
groupIds:
  - encryption
  - passphrase
  - service-vault
  - team-key
  - zero-knowledge
contributors: []
relatedBookIds: []
relatedKnowledgeIds:
  - vault.personal-key
  - vault.team-custody
  - vault.recovery
  - vault.grants
  - vault.rotation
  - vault.reset
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
  - service vault
  - passphrase
  - encryption
  - team key
  - zero knowledge
documentationUrls: []
---

The service vault protects provider credentials without giving the TreeSeed API a general decryption path.

Your personal passphrase encrypts your administrator private key in the browser. A separate random team vault key wraps credential keys and is independently granted to authorized administrators.

TreeSeed stores public keys, ciphertext, wrapped keys, salts, nonces, versions, and fingerprints. It never retains passphrases, plaintext provider tokens, derived keys, unlocked private keys, or decryptable team keys.

Unlocking is temporary and in-memory. Signing out or reaching the inactivity limit locks the browser controller.
