---
schemaVersion: treeseed.knowledge-page/v2
id: team.invitation
projectId: 4c520946-e4c3-460d-a50f-255b65c78451
bookRef:
  store: treedx
  model: book
  id: treeseed-team-administration
  path: books/team-administration.md
  revision: 1
  digest: sha256:23e3cb76f26e0a12710ce146cb3eabf34f770a8ae9fec1d50100505bc4605dda
slug: invitation
title: Team invitation consent
summary: Send, review, resend, revoke, and explicitly accept team invitations.
status: published
visibility: public
order: 40
groupIds:
  - accept
  - email-mismatch
  - expiry
  - invitation
  - resend
  - revoke
contributors: []
relatedBookIds: []
relatedKnowledgeIds:
  - team.membership
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
  - admin.team.invite-accept
  - admin.team.members
routePatterns:
  - /team-invites/[token]/accept
  - /app/teams/[teamId]/members
resourceTypes:
  - team-invitation
actionIds: []
keywords:
  - invitation
  - accept
  - resend
  - revoke
  - expiry
  - email mismatch
documentationUrls: []
---

Every invitation requires explicit recipient acceptance, including invitations sent to an existing TreeSeed user.

The acceptance page shows the team, invited email, proposed role, inviter, and expiration before any membership is created. A signed-in account with a different verified email cannot consume the invitation.

Resending refreshes delivery without creating duplicate pending invitations. Revocation and expiration make the token unusable. Replaying an already accepted token is safe only for the same recipient.
