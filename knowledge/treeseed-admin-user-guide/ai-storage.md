---
schemaVersion: treeseed.knowledge-page/v2
id: ai.storage
projectId: 4c520946-e4c3-460d-a50f-255b65c78451
bookRef:
  store: treedx
  model: book
  id: treeseed-admin-user-guide
  path: books/user-guide.md
  revision: 1
  digest: sha256:dcf81b7bb1de30fdaebb473bba84a63dae6cb7af91d945d3eb1495e9bab1abec
slug: ai-storage
title: Models and storage
summary: Models and storage in the team management interface.
status: published
visibility: authenticated
order: 80
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

Choose the model identifier or published training recipe and an authorized object-storage connection. Training and combined inference/training drafts require storage. This selection is a configuration reference, not blanket access to an R2 bucket.

Deployment must grant exact dataset/checkpoint paths and bounded credentials before an engine runs. Credentials remain in the team's vault and must never be entered as a model identifier, recipe or instance name. Live storage delivery is not yet qualified by saving a draft.
