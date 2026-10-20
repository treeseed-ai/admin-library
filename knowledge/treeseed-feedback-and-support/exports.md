---
schemaVersion: treeseed.knowledge-page/v2
id: feedback.exports
projectId: 4c520946-e4c3-460d-a50f-255b65c78451
bookRef:
  store: treedx
  model: book
  id: treeseed-feedback-and-support
  path: books/feedback-and-support.md
  revision: 1
  digest: sha256:f299eab796a35381e4ac5ef43b5305dc86bb3efe1f79fd832923035e9bd381f8
slug: exports
title: Privacy-safe feedback exports
summary: Prepare bounded feedback bundles for human review and AI-assisted remediation.
status: published
visibility: admin
order: 30
groupIds:
  - ai
  - export
  - jsonl
  - privacy
  - provenance
  - zip
contributors: []
relatedBookIds: []
relatedKnowledgeIds:
  - feedback.administration
  - feedback.triage
  - feedback.privacy
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
  - admin.feedback.collection
routePatterns:
  - /app/feedback
resourceTypes:
  - feedback-export
actionIds: []
keywords:
  - export
  - AI
  - JSONL
  - ZIP
  - privacy
  - provenance
documentationUrls: []
---

An export contains at most 500 selected or filtered records. The ZIP includes a policy manifest, agent-oriented JSONL, and a human-readable Markdown review.

Direct personal identifiers such as email, display name, username, and profile image are omitted. Opaque identifiers, route and build context, the message, status, and resolution history remain so work can be correlated safely.

Exports expire after 7 days. Creating an export records provenance but does not change feedback status.
