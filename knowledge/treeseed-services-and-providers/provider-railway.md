---
schemaVersion: treeseed.knowledge-page/v2
id: provider.railway
projectId: 4c520946-e4c3-460d-a50f-255b65c78451
bookRef:
  store: treedx
  model: book
  id: treeseed-services-and-providers
  path: books/services-and-providers.md
  revision: 1
  digest: sha256:24cdbe62e8633dffc1526f58c3303c049547a4676e64e31923f652baed4f6cd5
slug: provider-railway
title: Connecting Railway safely
summary: Record a workspace boundary and acknowledge the broader authority of
  shared Railway tokens.
status: published
visibility: authenticated
order: 120
groupIds:
  - api-token
  - blast-radius
  - railway
  - workspace
contributors: []
relatedBookIds: []
relatedKnowledgeIds:
  - services.connect
  - services.providers
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
capabilityIds: []
routePatterns: []
resourceTypes: []
actionIds: []
keywords:
  - railway
  - workspace
  - api token
  - blast radius
documentationUrls:
  - https://docs.railway.com/guides/public-api
---

Record the Railway workspace ID as non-secret metadata.

Railway workspace tokens may span several capabilities. Create a token in the exact workspace, verify that it matches the recorded workspace ID, and store it only in the encrypted Railway profile.

Use a dedicated workspace when stronger separation is required. Before revoking an old token, save and validate its replacement.
