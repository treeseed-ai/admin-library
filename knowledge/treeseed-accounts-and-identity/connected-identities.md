---
schemaVersion: treeseed.knowledge-page/v2
id: account.connected-identities
projectId: 4c520946-e4c3-460d-a50f-255b65c78451
bookRef:
  store: treedx
  model: book
  id: treeseed-accounts-and-identity
  path: books/accounts-and-identity.md
  revision: 1
  digest: sha256:5940970fe215984e7900fc9f9b85c4e76a9ea9edf12c93f5616bea9026697f4c
slug: connected-identities
title: Connected sign-in identities
summary: Understand how external sign-in providers attach to your account and
  when they may be removed.
status: published
visibility: authenticated
order: 20
groupIds:
  - github
  - google
  - identity
  - provider
  - sign-in
contributors: []
relatedBookIds: []
relatedKnowledgeIds:
  - account.security
  - account.emails
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
  - admin.account.identity
routePatterns:
  - /app/account
resourceTypes:
  - account
actionIds:
  - account.provider.connect
  - account.provider.disconnect
keywords:
  - provider
  - sign-in
  - identity
  - github
  - google
documentationUrls: []
---

Connected identities let an approved provider authenticate the same TreeSeed account. Connecting a provider does not grant that provider access to team service credentials.

Before disconnecting an identity, keep another working sign-in method: a password or a second connected provider. Review active sessions after any unexpected provider change.
