---
schemaVersion: treeseed.knowledge-page/v2
id: vault.grants
projectId: 4c520946-e4c3-460d-a50f-255b65c78451
bookRef:
  store: treedx
  model: book
  id: treeseed-credential-security
  path: books/credential-security.md
  revision: 1
  digest: sha256:e93c794a57eb4172e152306d2585a1ee2fd51f2d37e123f3eb7a277940849d24
slug: grants
title: Administrator vault grants
summary: Give another administrator cryptographic access without sharing
  passphrases or provider credentials.
status: published
visibility: authenticated
order: 10
groupIds:
  - administrator
  - grant
  - revoke
  - wrapped-team-key
contributors: []
relatedBookIds: []
relatedKnowledgeIds:
  - vault.recovery
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
  - admin.services.vault
routePatterns:
  - /app/services/vault
resourceTypes:
  - team-vault-grant
actionIds: []
keywords:
  - grant
  - revoke
  - administrator
  - wrapped team key
documentationUrls: []
---

Each administrator registers a separate public key and protects their private key with a personal passphrase.

Granting access opens the team vault key only in your browser and wraps it to the recipient’s public key. The recipient never learns your passphrase, and you never learn theirs.

Revoke cryptographic access separately from changing a team role. After removing a credential administrator or suspecting key compromise, rotate the team vault key for the remaining grants.
