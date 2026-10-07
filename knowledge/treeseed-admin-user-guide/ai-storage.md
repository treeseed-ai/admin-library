---
schemaVersion: treeseed.knowledge-page/v1
id: ai.storage
bookId: treeseed-admin-user-guide
slug: ai-storage
title: Models and storage
summary: Models and storage in the team management interface.
status: published
visibility: authenticated
order: 80
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

Choose the model identifier or published training recipe and an authorized object-storage connection. Training and combined inference/training drafts require storage. This selection is a configuration reference, not blanket access to an R2 bucket.

Deployment must grant exact dataset/checkpoint paths and bounded credentials before an engine runs. Credentials remain in the team's vault and must never be entered as a model identifier, recipe or instance name. Live storage delivery is not yet qualified by saving a draft.

