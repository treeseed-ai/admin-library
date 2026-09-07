---
schemaVersion: treeseed.knowledge-page/v1
id: provider.hyperstack
bookId: treeseed-admin-user-guide
slug: provider-hyperstack
title: Hyperstack account access
summary: Hyperstack account access in the team management interface.
status: published
visibility: authenticated
order: 100
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

