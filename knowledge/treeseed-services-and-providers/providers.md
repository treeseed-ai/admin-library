---
schemaVersion: treeseed.knowledge-page/v2
id: services.providers
projectId: 4c520946-e4c3-460d-a50f-255b65c78451
bookRef:
  store: treedx
  model: book
  id: treeseed-services-and-providers
  path: books/services-and-providers.md
  revision: 1
  digest: sha256:24cdbe62e8633dffc1526f58c3303c049547a4676e64e31923f652baed4f6cd5
slug: providers
title: Provider capabilities and permission boundaries
summary: Compare supported providers without treating shared capability types as
  shared credentials.
status: published
visibility: authenticated
order: 130
groupIds:
  - cloudflare
  - github
  - openbao
  - permissions
  - railway
contributors: []
relatedBookIds: []
relatedKnowledgeIds:
  - provider.github
  - provider.cloudflare
  - provider.railway
  - provider.openbao
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
  - admin.services.collection
  - admin.services.create
  - admin.services.detail
routePatterns:
  - /app/services
  - /app/services/new
  - /app/services/[connectionId]
resourceTypes:
  - service-provider
actionIds: []
keywords:
  - github
  - cloudflare
  - railway
  - openbao
  - permissions
documentationUrls: []
---

Provider connections are modular. Different providers may become eligible for the same capability while retaining different account models, permission limits, and credential profiles.

Prefer the narrowest provider identity and credential scope available. Split credentials by capability when the provider supports that separation. When a provider exposes one broad token, use a dedicated account or workspace to reduce its blast radius.
