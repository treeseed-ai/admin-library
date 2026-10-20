---
schemaVersion: treeseed.knowledge-page/v2
id: provider.hyperstack
projectId: 4c520946-e4c3-460d-a50f-255b65c78451
bookRef:
  store: treedx
  model: book
  id: treeseed-admin-user-guide
  path: books/user-guide.md
  revision: 1
  digest: sha256:dcf81b7bb1de30fdaebb473bba84a63dae6cb7af91d945d3eb1495e9bab1abec
slug: provider-hyperstack
title: Hyperstack account access
summary: Hyperstack account access in the team management interface.
status: published
visibility: authenticated
order: 100
groupIds: []
contributors: []
relatedBookIds: []
relatedKnowledgeIds:
  - ai.deployments
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
routePatterns:
  - /app/ai*
resourceTypes: []
actionIds: []
keywords:
  - AI
documentationUrls: []
---

In Connections, choose Provide AI service for vLLM inference, Run training for Axolotl, or both. Save the Hyperstack account credential through the account step; it is held in your team's vault.

Then open Manage AI to configure instances using that connection. One draft can select inference and training together, but compatible GPU sizing and runtime qualification must precede deployment. Hyperstack is used here for AI hosting, not as a Kata capacity provider. No nested-virtualization capability is assumed.
