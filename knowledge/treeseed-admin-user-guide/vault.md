---
schemaVersion: treeseed.knowledge-page/v1
id: services.vaults
bookId: treeseed-admin-user-guide
slug: vault
title: Your team's credential vault
summary: Understand managed credential storage and the current custom-vault
  setup screen.
status: published
visibility: authenticated
order: 0
contributors: []
relatedBookIds: []
relatedKnowledgeIds:
  - services.vaults.trust
  - services.vaults.external
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
  - admin.services.detail
routePatterns:
  - /app/services/vaults
resourceTypes:
  - team-vault
actionIds: []
keywords:
  - vault
  - OpenBao
  - credentials
documentationUrls: []
---

A service connection controls what TreeSeed can do with a provider account. A vault stores the credentials needed for those operations. They are different responsibilities.

## No setup for managed storage
TreeSeed supplies managed OpenBao storage for service credentials. Keep using Connections to configure provider accounts; you do not need to create a personal vault key or put tokens in a project repository.

## Connecting your own vault
The current local Vault screen lets you explore an OpenBao or HashiCorp Vault configuration. **Verify and connect is currently disabled.** Advancing through the wizard validates the draft fields; it does not establish an external vault or move existing credentials. Your current managed storage remains in use.

The intended completed transition is one custom vault replacing the team's managed storage after access verification and credential migration. Do not assume that transition has happened while verification is unavailable.

