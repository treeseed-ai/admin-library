---
schemaVersion: treeseed.knowledge-page/v1
id: services.vaults.trust
bookId: treeseed-admin-user-guide
slug: vault-trust
title: How vault custody protects credentials
summary: Understand who can retrieve credentials and where sensitive values
  should never be placed.
status: published
visibility: authenticated
order: 0
contributors: []
relatedBookIds: []
relatedKnowledgeIds:
  - services.vaults
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

TreeSeed keeps service credential values in its managed vault instead of embedding them in Platform configuration or project source. Provider tasks use authorized server-side credential access.

## The trust boundary
Vault storage is not a zero-knowledge promise. Authorized TreeSeed control-plane processes and operation runners need access to credential values to perform the tasks you enable. The operator of a vault also controls its infrastructure and access policies.

Do not place tokens, private keys or vault login material in documentation, Git, URLs, logs, screenshots or support messages. A provider account identifier or vault address is not the same as a credential.

## External vaults
Using your own vault changes who operates credential storage; it does not remove the control plane's need for authorized access. External setup must verify TLS trust, network access and scoped authentication before credentials can be moved. The current local configuration screen does not perform that transition: its verification action is disabled.

