---
schemaVersion: treeseed.knowledge-page/v2
id: team.visibility
projectId: 4c520946-e4c3-460d-a50f-255b65c78451
bookRef:
  store: treedx
  model: book
  id: treeseed-team-administration
  path: books/team-administration.md
  revision: 1
  digest: sha256:23e3cb76f26e0a12710ce146cb3eabf34f770a8ae9fec1d50100505bc4605dda
slug: visibility
title: Team profile visibility
summary: Control whether the team identity profile is public without changing
  project or knowledge-plane visibility.
status: published
visibility: team
order: 140
groupIds:
  - private
  - profile
  - public
  - visibility
contributors: []
relatedBookIds: []
relatedKnowledgeIds:
  - team.settings
  - team.overview
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
  - admin.team.edit
routePatterns:
  - /app/teams/[teamId]/edit
resourceTypes:
  - team
actionIds:
  - team.visibility.update
keywords:
  - visibility
  - public
  - private
  - profile
documentationUrls: []
---

Team profile visibility controls only the public team identity page. It does not make projects public or private and does not select where project knowledge is indexed.

Public profiles expose approved identity fields. Memberships, roles, emails, operational counts, billing, hosts, and private metadata remain redacted.
