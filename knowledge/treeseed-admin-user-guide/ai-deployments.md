---
schemaVersion: treeseed.knowledge-page/v2
id: ai.deployments
projectId: 4c520946-e4c3-460d-a50f-255b65c78451
bookRef:
  store: treedx
  model: book
  id: treeseed-admin-user-guide
  path: books/user-guide.md
  revision: 1
  digest: sha256:dcf81b7bb1de30fdaebb473bba84a63dae6cb7af91d945d3eb1495e9bab1abec
slug: ai-deployments
title: AI instances and drafts
summary: AI instances and drafts in the team management interface.
status: published
visibility: authenticated
order: 70
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

An AI instance configuration is separate from its Hyperstack service connection. A connection stores account access; an instance describes the project, workload and schedule using that account.

Use the instance list to search and open saved drafts. The wizard walks through Purpose, Hosting, Models and storage, Schedule and Review. Save draft persists your choices without renting a machine. Existing drafts can be edited or deleted. Deleting an unprovisioned draft does not affect running cloud machines.

GPU selection, exact engine releases, scoped storage grants and live deployment qualification remain required before activation. A draft is not a deployed endpoint or a completed training job.
