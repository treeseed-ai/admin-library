---
schemaVersion: treeseed.knowledge-page/v2
id: provider.openbao
projectId: 4c520946-e4c3-460d-a50f-255b65c78451
bookRef:
  store: treedx
  model: book
  id: treeseed-services-and-providers
  path: books/services-and-providers.md
  revision: 1
  digest: sha256:24cdbe62e8633dffc1526f58c3303c049547a4676e64e31923f652baed4f6cd5
slug: provider-openbao
title: Connecting OpenBao or HashiCorp Vault
summary: Use workload identity and references instead of storing a reusable vault token.
status: published
visibility: authenticated
order: 110
groupIds:
  - hashicorp-vault
  - jwt
  - oidc
  - openbao
  - workload-identity
contributors: []
relatedBookIds: []
relatedKnowledgeIds:
  - services.external-vault
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
  - openbao
  - hashicorp vault
  - oidc
  - jwt
  - workload identity
documentationUrls:
  - https://openbao.org/docs/auth/jwt/
---

Configure an HTTPS vault address, secrets mount, and an OIDC/JWT role dedicated to TreeSeed operations.

The role should authorize only expected paths and operations. The operations runner exchanges its workload identity for short-lived access when an authorized unattended operation begins.

Do not enter a personal, root, or long-lived vault token. External vaults do not store or recover TreeSeed personal passphrases.
