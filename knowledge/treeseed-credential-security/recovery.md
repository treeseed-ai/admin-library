---
schemaVersion: treeseed.knowledge-page/v2
id: vault.recovery
projectId: 4c520946-e4c3-460d-a50f-255b65c78451
bookRef:
  store: treedx
  model: book
  id: treeseed-credential-security
  path: books/credential-security.md
  revision: 1
  digest: sha256:e93c794a57eb4172e152306d2585a1ee2fd51f2d37e123f3eb7a277940849d24
slug: recovery
title: Step 3 — Plan vault recovery
summary: Know when another administrator can restore access and when protected
  credentials must be reentered.
status: published
visibility: authenticated
order: 50
groupIds:
  - forgotten-passphrase
  - recovery
  - sole-administrator
  - step-3
contributors: []
relatedBookIds: []
relatedKnowledgeIds:
  - vault.grants
  - vault.rotation
  - vault.reset
  - vault.overview
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
  - step 3
  - recovery
  - forgotten passphrase
  - sole administrator
documentationUrls: []
---

Another currently authorized credential administrator can grant a replacement personal key access after you forget your passphrase.

If the sole credential administrator loses the passphrase, nobody—including TreeSeed support—can recover the old ciphertext. Reset the vault and reenter every protected provider credential.

For resilient custody, grant at least one other trusted administrator and review grants after team role changes. A team role alone does not create or revoke cryptographic access.
