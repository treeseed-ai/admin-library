---
schemaVersion: treeseed.knowledge-page/v2
id: account.emails
projectId: 4c520946-e4c3-460d-a50f-255b65c78451
bookRef:
  store: treedx
  model: book
  id: treeseed-accounts-and-identity
  path: books/accounts-and-identity.md
  revision: 1
  digest: sha256:5940970fe215984e7900fc9f9b85c4e76a9ea9edf12c93f5616bea9026697f4c
slug: emails
title: Email addresses and verification
summary: Add, verify, promote, and remove account email addresses without
  weakening account recovery.
status: published
visibility: authenticated
order: 40
groupIds:
  - email
  - primary
  - recovery
  - verification
contributors: []
relatedBookIds: []
relatedKnowledgeIds:
  - account.identity
  - account.security
  - account.connected-identities
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
  - admin.account.identity
routePatterns:
  - /app/account
resourceTypes:
  - account
actionIds:
  - account.email.add
  - account.email.verify
  - account.email.primary
  - account.email.remove
keywords:
  - email
  - verification
  - primary
  - recovery
documentationUrls: []
---

## What verification proves

TreeSeed sends a one-time link to each new address. The address remains pending until that exact link is accepted. Verification proves access to the mailbox; it does not change the primary address automatically.

## Keep a recovery path

An account must retain a usable verified address. Set another verified address as primary before removing the current primary address. If a link expires, request a new message from the email row rather than adding the address again.
