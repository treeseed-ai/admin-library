---
schemaVersion: treeseed.knowledge-page/v2
id: vault.personal-key
projectId: 4c520946-e4c3-460d-a50f-255b65c78451
bookRef:
  store: treedx
  model: book
  id: treeseed-credential-security
  path: books/credential-security.md
  revision: 1
  digest: sha256:e93c794a57eb4172e152306d2585a1ee2fd51f2d37e123f3eb7a277940849d24
slug: personal-key
title: Step 1 — Create personal vault access
summary: Create an administrator key protected by a personal passphrase that is
  separate from your account password.
status: published
visibility: authenticated
order: 30
groupIds:
  - account-password
  - administrator-key
  - personal-passphrase
  - step-1
contributors: []
relatedBookIds: []
relatedKnowledgeIds:
  - vault.team-custody
  - vault.recovery
  - vault.rotation
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
  - user-vault-key
actionIds: []
keywords:
  - step 1
  - personal passphrase
  - administrator key
  - account password
documentationUrls: []
---

Step 1 creates a public/private encryption keypair in your browser.

Choose a new **personal vault passphrase**. This is not your TreeSeed account password. The passphrase derives a local encryption key that protects the private half of your administrator keypair.

Only the public key and encrypted private-key envelope are sent to TreeSeed. The passphrase and derived key remain in browser memory and are discarded after the operation.

You will re-enter this same passphrase in step 2. Step 2 does not create another passphrase.
