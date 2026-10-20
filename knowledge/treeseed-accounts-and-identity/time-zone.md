---
schemaVersion: treeseed.knowledge-page/v2
id: account.time-zone
projectId: 4c520946-e4c3-460d-a50f-255b65c78451
bookRef:
  store: treedx
  model: book
  id: treeseed-accounts-and-identity
  path: books/accounts-and-identity.md
  revision: 1
  digest: sha256:5940970fe215984e7900fc9f9b85c4e76a9ea9edf12c93f5616bea9026697f4c
slug: time-zone
title: Display time zone
summary: Choose the IANA time zone used to format dates and times throughout
  authenticated TreeSeed pages.
status: published
visibility: authenticated
order: 100
groupIds:
  - date
  - iana
  - time-zone
  - timestamp
  - timezone
contributors: []
relatedBookIds: []
relatedKnowledgeIds:
  - account.identity
  - account.sessions
  - account.notifications
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
  - account-preferences
actionIds:
  - account.time-zone.update
keywords:
  - timezone
  - time zone
  - date
  - timestamp
  - IANA
documentationUrls: []
---

TreeSeed stores each event as an absolute instant. Your display time zone changes only how that instant is presented in the interface.

Choose the place whose daylight-saving rules you want TreeSeed to follow. The same setting is used during server rendering and later page updates so timestamps do not shift after loading.
