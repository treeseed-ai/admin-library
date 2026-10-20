---
schemaVersion: treeseed.knowledge-page/v2
id: team.activity
projectId: 4c520946-e4c3-460d-a50f-255b65c78451
bookRef:
  store: treedx
  model: book
  id: treeseed-team-administration
  path: books/team-administration.md
  revision: 1
  digest: sha256:23e3cb76f26e0a12710ce146cb3eabf34f770a8ae9fec1d50100505bc4605dda
slug: activity
title: Team activity
summary: Read the human-centered history of security-sensitive team changes.
status: published
visibility: team
order: 10
groupIds:
  - activity
  - actor
  - audit
  - changes
  - history
contributors: []
relatedBookIds: []
relatedKnowledgeIds:
  - team.overview
  - team.membership
  - team.lifecycle
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
  - admin.team.overview
routePatterns:
  - /app/teams/[teamId]
resourceTypes:
  - audit-event
actionIds:
  - team.audit.read
keywords:
  - activity
  - audit
  - actor
  - changes
  - history
documentationUrls: []
---

Activity entries identify what happened, when it happened in your time zone, and the person who performed the action when a public profile is available.

Technical correlation identifiers are retained for diagnostics but are not the primary human display. Credential values and other secrets never belong in audit details.
