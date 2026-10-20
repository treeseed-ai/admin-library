---
schemaVersion: treeseed.knowledge-page/v2
id: provider.cloudflare
projectId: 4c520946-e4c3-460d-a50f-255b65c78451
bookRef:
  store: treedx
  model: book
  id: treeseed-services-and-providers
  path: books/services-and-providers.md
  revision: 1
  digest: sha256:24cdbe62e8633dffc1526f58c3303c049547a4676e64e31923f652baed4f6cd5
slug: provider-cloudflare
title: Connecting Cloudflare safely
summary: Separate runtime, DNS, and storage tokens and restrict each one to
  exact account or zone resources.
status: published
visibility: authenticated
order: 90
groupIds:
  - api-token
  - cloudflare
  - dns
  - pages
  - r2
  - workers
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
  - cloudflare
  - pages
  - workers
  - dns
  - r2
  - api token
documentationUrls:
  - https://developers.cloudflare.com/fundamentals/api/get-started/create-token/
---

Record the Cloudflare account ID as non-secret metadata. Never use the Global API Key.

Create separate custom API tokens for frontend runtime, DNS, and storage capabilities. Grant only the permission named by the enabled capability and restrict resources to the connected account or exact managed zones.

Save each one-time token in its matching encrypted profile. Rotating one capability token should not require exposing or replacing unrelated credentials.
