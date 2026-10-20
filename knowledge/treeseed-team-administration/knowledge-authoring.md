---
schemaVersion: treeseed.knowledge-page/v2
id: knowledge.authoring
projectId: 4c520946-e4c3-460d-a50f-255b65c78451
bookRef:
  store: treedx
  model: book
  id: treeseed-team-administration
  path: books/team-administration.md
  revision: 1
  digest: sha256:23e3cb76f26e0a12710ce146cb3eabf34f770a8ae9fec1d50100505bc4605dda
slug: knowledge-authoring
title: Authoring team knowledge
summary: Create repository-native books and pages through recoverable TreeDX
  workspaces and review branches.
status: published
visibility: team
order: 90
groupIds:
  - authoring
  - books
  - knowledge
contributors: []
relatedBookIds: []
relatedKnowledgeIds:
  - team.roles
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
  - admin.knowledge.workbench
routePatterns:
  - /app/knowledge
resourceTypes:
  - knowledge
actionIds:
  - knowledge.workspace.create
  - knowledge.review.submit
keywords:
  - TreeDX workspace
  - book editor
  - knowledge review
documentationUrls: []
---

## What the workbench changes

The knowledge workbench edits files in the selected project's Git repository. TreeDX provides a recoverable working copy, search, relationships, and a reviewable diff without moving the content into the application database.

Saving a draft does not publish it. A submission commits an operation-scoped branch for review. A reviewer can inspect the diff, rendered page, relationships, visibility, and affected knowledge packs before approval.

## Permissions

Knowledge authors can create and update drafts. Knowledge reviewers can review changes. Publishing and book management require their explicit knowledge permissions; broad access to unrelated team administration is not required.

## Safe collaboration

The editor rejects executable imports, arbitrary JSX, raw HTML, and unsafe links. If the repository or draft changed after you opened it, TreeSeed stops the save and asks you to reconcile the conflict instead of overwriting newer work.
