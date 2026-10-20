---
schemaVersion: treeseed.knowledge-page/v2
id: account.security
projectId: 4c520946-e4c3-460d-a50f-255b65c78451
bookRef:
  store: treedx
  model: book
  id: treeseed-accounts-and-identity
  path: books/accounts-and-identity.md
  revision: 1
  digest: sha256:5940970fe215984e7900fc9f9b85c4e76a9ea9edf12c93f5616bea9026697f4c
slug: security
title: Passwords, email addresses, and connected identities
summary: Manage account sign-in methods without weakening recovery or exposing
  private addresses.
status: published
visibility: authenticated
order: 80
groupIds:
  - email
  - password
  - provider
  - security
  - verification
contributors: []
relatedBookIds: []
relatedKnowledgeIds:
  - account.identity
  - account.sessions
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
  - admin.account.identity
routePatterns:
  - /app/account
resourceTypes:
  - account
actionIds: []
keywords:
  - password
  - provider
  - email
  - verification
  - security
documentationUrls: []
---

TreeSeed can use a password, a configured identity provider, or both. Each connected identity should belong to you and remain recoverable.

## Password changes

Changing a password requires the current password when one already exists. New passwords use the same strength and confirmation checks as registration and password recovery.

## Verified email

A delivered confirmation message does not verify an address by itself. The one-time confirmation link must be opened successfully before the address becomes verified.

## Connected providers

Do not remove the last usable sign-in method. Before disconnecting a provider, confirm that another provider or password works.
