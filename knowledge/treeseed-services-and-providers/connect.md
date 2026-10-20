---
schemaVersion: treeseed.knowledge-page/v2
id: services.connect
projectId: 4c520946-e4c3-460d-a50f-255b65c78451
bookRef:
  store: treedx
  model: book
  id: treeseed-services-and-providers
  path: books/services-and-providers.md
  revision: 1
  digest: sha256:24cdbe62e8633dffc1526f58c3303c049547a4676e64e31923f652baed4f6cd5
slug: connect
title: Connecting a provider service
summary: Choose a provider account, enable only required capabilities, and
  review credential custody before saving.
status: published
visibility: authenticated
order: 30
groupIds:
  - capability
  - connect-service
  - credentials
  - provider
contributors: []
relatedBookIds: []
relatedKnowledgeIds:
  - services.providers
  - services.credentials
  - vault.overview
  - provider.github
  - provider.cloudflare
  - provider.railway
  - provider.openbao
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
  - admin.services.create
routePatterns:
  - /app/services/new
resourceTypes:
  - team-service-connection
actionIds: []
keywords:
  - connect service
  - provider
  - capability
  - credentials
documentationUrls: []
---

Start with the provider account boundary, then enable the capabilities this team expects to use.

Account IDs, organization names, installation IDs, and workspace IDs are non-secret metadata. Provider tokens, private keys, and other authentication material belong in encrypted credential profiles after the connection exists.

Select only capabilities the team needs. Planned capabilities describe future compatibility but do not prove a deployment or resource mutation exists.
