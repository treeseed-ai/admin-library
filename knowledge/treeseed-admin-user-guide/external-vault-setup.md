---
schemaVersion: treeseed.knowledge-page/v1
id: services.vaults.external
bookId: treeseed-admin-user-guide
slug: external-vault-setup
title: Review an external vault configuration
summary: Use the local wizard without confusing a validated draft with a
  connected vault.
status: published
visibility: authenticated
order: 0
contributors: []
relatedBookIds: []
relatedKnowledgeIds:
  - services.vaults
  - services.vaults.trust
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

A team owner or service administrator can open **Connect your own vault** on the Vault page.

1. Choose OpenBao or HashiCorp Vault.
2. Enter the HTTPS origin of the vault, such as `https://vault.example.com`. Do not include credentials, URL paths, query parameters or fragments.
3. Enter the KV v2 secrets-engine mount supplied by your vault administrator, such as `secret`.
4. Review the access information. Back and the step controls let you revise the draft.

## Current limitation
**Connection verification is currently unavailable.** The disabled Verify and connect button means this screen cannot yet create an external-vault binding, authenticate with AppRole or migrate existing credentials. Field validation is not a connectivity or permission check. Keep using the provided managed vault for current service connections.

Do not supply a root token or paste secrets into the address or mount fields. A completed backend integration must establish scoped authentication and verify destination access before changing active storage.

