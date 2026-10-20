---
schemaVersion: treeseed.knowledge-page/v2
id: team.removal
projectId: 4c520946-e4c3-460d-a50f-255b65c78451
bookRef:
  store: treedx
  model: book
  id: treeseed-team-administration
  path: books/team-administration.md
  revision: 1
  digest: sha256:23e3cb76f26e0a12710ce146cb3eabf34f770a8ae9fec1d50100505bc4605dda
slug: removal
title: Removing a member or leaving
summary: Resolve ownership and resource blockers before access is removed.
status: published
visibility: team
order: 100
groupIds:
  - blockers
  - leave
  - lost-access
  - remove
contributors: []
relatedBookIds: []
relatedKnowledgeIds:
  - team.membership
  - team.ownership
  - team.role-changes
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
  - team.member.remove
  - team.member.leave
keywords:
  - remove
  - leave
  - blockers
  - lost access
documentationUrls: []
---

Removal and self-leave revoke team access immediately after the operation succeeds. TreeSeed first checks ownership and any team-owned responsibilities that must be reassigned.

Resolve every displayed blocker at its linked management page. A sole owner must transfer or grant ownership before leaving or being removed.
