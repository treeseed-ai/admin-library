---
schemaVersion: treeseed.knowledge-page/v2
id: team.settings
projectId: 4c520946-e4c3-460d-a50f-255b65c78451
bookRef:
  store: treedx
  model: book
  id: treeseed-team-administration
  path: books/team-administration.md
  revision: 1
  digest: sha256:23e3cb76f26e0a12710ce146cb3eabf34f770a8ae9fec1d50100505bc4605dda
slug: settings
title: Team identity and public visibility
summary: Maintain the team name, display identity, logo, summary, and profile
  visibility.
status: published
visibility: authenticated
order: 130
groupIds:
  - conflict
  - identity
  - public-profile
  - team-settings
  - visibility
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
  - admin.team.edit
routePatterns:
  - /app/teams/[teamId]/edit
resourceTypes:
  - team
actionIds: []
keywords:
  - team settings
  - identity
  - public profile
  - visibility
  - conflict
documentationUrls: []
---

Team settings contain identity owned by the team domain. Project, host, capacity, knowledge, and commerce settings remain in their own domains.

The team name is used for the public profile address. The display name is presentation only and is never used for ambiguous lookup.

Updates use optimistic version checks. If another administrator saves first, reload the current state and deliberately reapply your change rather than overwriting it silently.
