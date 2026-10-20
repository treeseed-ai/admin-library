---
schemaVersion: treeseed.knowledge-page/v2
id: team.role-changes
projectId: 4c520946-e4c3-460d-a50f-255b65c78451
bookRef:
  store: treedx
  model: book
  id: treeseed-team-administration
  path: books/team-administration.md
  revision: 1
  digest: sha256:23e3cb76f26e0a12710ce146cb3eabf34f770a8ae9fec1d50100505bc4605dda
slug: role-changes
title: Changing a member role
summary: Review how a role change affects visible controls and durable authorization.
status: published
visibility: team
order: 110
groupIds:
  - access
  - change
  - permission
  - role
contributors: []
relatedBookIds: []
relatedKnowledgeIds:
  - team.roles
  - team.ownership
  - team.removal
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
  - admin.team.members
routePatterns:
  - /app/teams/[teamId]/members
resourceTypes:
  - team-membership
actionIds:
  - team.member.role.update
keywords:
  - role
  - access
  - permission
  - change
documentationUrls: []
---

Choose the role whose responsibilities match the member’s work. The change takes effect in both the interface and API authorization after it succeeds.

Project leads cannot create, demote, remove, or replace owners. The only owner cannot select a role that would leave the team ownerless.
