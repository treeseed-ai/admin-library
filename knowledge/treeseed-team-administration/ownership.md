---
schemaVersion: treeseed.knowledge-page/v2
id: team.ownership
projectId: 4c520946-e4c3-460d-a50f-255b65c78451
bookRef:
  store: treedx
  model: book
  id: treeseed-team-administration
  path: books/team-administration.md
  revision: 1
  digest: sha256:23e3cb76f26e0a12710ce146cb3eabf34f770a8ae9fec1d50100505bc4605dda
slug: ownership
title: Team ownership
summary: Grant or transfer ownership without leaving a team with no accountable owner.
status: published
visibility: team
order: 90
groupIds:
  - last-owner
  - owner
  - ownership
  - transfer
contributors: []
relatedBookIds: []
relatedKnowledgeIds:
  - team.roles
  - team.role-changes
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
  - team.ownership.transfer
  - team.owner.grant
  - team.owner.remove
keywords:
  - owner
  - ownership
  - transfer
  - last owner
documentationUrls: []
---

Owners hold the team’s highest security authority. Only an owner may grant, remove, or transfer ownership.

TreeSeed protects the last owner transactionally. Add or transfer ownership before the only owner changes role, leaves, or is removed. Ownership access and credential-vault grants are separate; update both when responsibilities change.
