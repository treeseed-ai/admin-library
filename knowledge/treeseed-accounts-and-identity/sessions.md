---
schemaVersion: treeseed.knowledge-page/v2
id: account.sessions
projectId: 4c520946-e4c3-460d-a50f-255b65c78451
bookRef:
  store: treedx
  model: book
  id: treeseed-accounts-and-identity
  path: books/accounts-and-identity.md
  revision: 1
  digest: sha256:5940970fe215984e7900fc9f9b85c4e76a9ea9edf12c93f5616bea9026697f4c
slug: sessions
title: Account sessions and device access
summary: Review signed-in devices, timestamps, network addresses, and safe
  session revocation.
status: published
visibility: authenticated
order: 90
groupIds:
  - devices
  - ip-address
  - revoke
  - sessions
  - sign-out
contributors: []
relatedBookIds: []
relatedKnowledgeIds:
  - account.security
  - account.deletion
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
  - admin.account.sessions
routePatterns:
  - /app/account/sessions
resourceTypes:
  - account-session
actionIds: []
keywords:
  - sessions
  - devices
  - revoke
  - ip address
  - sign out
documentationUrls: []
---

Each session represents a browser or device that can currently act as your account.

The list shows the user agent, recorded network address when available, creation time, and most recent activity using your account time zone.

## Revoking access

Revoke sessions you do not recognize or no longer use. The current session is protected from accidental inline revocation; use **Sign out** for the device you are using now.

After a session is revoked, requests carrying that session must be rejected.
