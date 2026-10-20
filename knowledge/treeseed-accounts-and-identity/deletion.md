---
schemaVersion: treeseed.knowledge-page/v2
id: account.deletion
projectId: 4c520946-e4c3-460d-a50f-255b65c78451
bookRef:
  store: treedx
  model: book
  id: treeseed-accounts-and-identity
  path: books/accounts-and-identity.md
  revision: 1
  digest: sha256:5940970fe215984e7900fc9f9b85c4e76a9ea9edf12c93f5616bea9026697f4c
slug: deletion
title: Permanently deleting an account
summary: Understand blockers, reauthentication, confirmation, and the access
  removed by deletion.
status: published
visibility: authenticated
order: 30
groupIds:
  - blockers
  - delete-account
  - irreversible
  - reauthentication
contributors: []
relatedBookIds: []
relatedKnowledgeIds:
  - account.security
  - account.sessions
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
  - admin.account.delete
routePatterns:
  - /app/account/delete
resourceTypes:
  - account
actionIds: []
keywords:
  - delete account
  - blockers
  - reauthentication
  - irreversible
documentationUrls: []
---

Account deletion is irreversible. It signs out every device and removes the account data allowed by retention and audit policy.

TreeSeed checks for responsibilities that would be orphaned, such as sole team ownership. Resolve every blocker before trying again.

Deletion requires recent reauthentication and the exact confirmation phrase shown in the form. A failed confirmation or password check must leave the account unchanged.
