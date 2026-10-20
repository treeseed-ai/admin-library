---
schemaVersion: treeseed.knowledge-page/v2
id: vault.team-custody
projectId: 4c520946-e4c3-460d-a50f-255b65c78451
bookRef:
  store: treedx
  model: book
  id: treeseed-credential-security
  path: books/credential-security.md
  revision: 1
  digest: sha256:e93c794a57eb4172e152306d2585a1ee2fd51f2d37e123f3eb7a277940849d24
slug: team-custody
title: Step 2 — Initialize team credential custody
summary: Reuse the step-1 passphrase to unlock your key and wrap a new random
  team vault key.
status: published
visibility: authenticated
order: 80
groupIds:
  - key-wrapping
  - same-passphrase
  - step-2
  - team-vault-key
contributors: []
relatedBookIds: []
relatedKnowledgeIds:
  - vault.personal-key
  - vault.recovery
  - vault.grants
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
  - step 2
  - same passphrase
  - team vault key
  - key wrapping
documentationUrls: []
---

Enter the **same personal vault passphrase you created in step 1**.

The browser uses it to unlock your encrypted administrator private key. It then creates a random team vault key and wraps access to that key for your administrator identity.

This step does not create a second passphrase, a shared team passphrase, or a recoverable server key. Your personal passphrase remains local and is never sent to or stored by TreeSeed.

Other credential administrators use their own personal keys and their own passphrases.
