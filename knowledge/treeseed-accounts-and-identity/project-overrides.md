---
schemaVersion: treeseed.knowledge-page/v2
id: account.project-overrides
projectId: 4c520946-e4c3-460d-a50f-255b65c78451
bookRef:
  store: treedx
  model: book
  id: treeseed-accounts-and-identity
  path: books/accounts-and-identity.md
  revision: 1
  digest: sha256:5940970fe215984e7900fc9f9b85c4e76a9ea9edf12c93f5616bea9026697f4c
slug: project-overrides
title: Project notification overrides
summary: Replace the all-project notification choices for selected projects
  without changing the global policy.
status: published
visibility: authenticated
order: 70
groupIds:
  - content
  - notifications
  - overrides
  - projects
contributors: []
relatedBookIds: []
relatedKnowledgeIds:
  - account.notifications
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
  - admin.account.notifications
routePatterns:
  - /app/account/notifications
resourceTypes:
  - notification-preferences
actionIds:
  - account.notifications.override
keywords:
  - notifications
  - projects
  - overrides
  - content
documentationUrls: []
---

The all-project choices are the default for every project you can access. Selecting a project override opens a separate set of content choices for that project.

An override replaces—not adds to—the default choices. Remove the project from the override list to make it inherit the all-project policy again.
