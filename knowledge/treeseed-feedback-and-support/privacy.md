---
schemaVersion: treeseed.knowledge-page/v2
id: feedback.privacy
projectId: 4c520946-e4c3-460d-a50f-255b65c78451
bookRef:
  store: treedx
  model: book
  id: treeseed-feedback-and-support
  path: books/feedback-and-support.md
  revision: 1
  digest: sha256:f299eab796a35381e4ac5ef43b5305dc86bb3efe1f79fd832923035e9bd381f8
slug: privacy
title: Feedback privacy boundary
summary: Learn which context is stored, who can inspect it, and how retention works.
status: published
visibility: authenticated
order: 40
groupIds:
  - audit
  - contact
  - identity
  - privacy
  - retention
contributors: []
relatedBookIds: []
relatedKnowledgeIds:
  - feedback.submitting
  - feedback.screenshot-privacy
  - feedback.exports
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
  - admin.feedback.submit
  - admin.feedback.detail
routePatterns:
  - /app/*
resourceTypes:
  - feedback-privacy
actionIds: []
keywords:
  - privacy
  - identity
  - retention
  - audit
  - contact
documentationUrls: []
---

Feedback text and private attachment metadata are durable feedback records. Audit events contain correlation identifiers and status metadata only; they do not duplicate messages, email addresses, browser details, or images.

Only platform administrators can read reports. Attachment and export downloads pass through authorized, no-store API responses and never reveal raw storage keys or provider URLs.

Feedback text and status history remain for auditability. Screenshots expire 90 days after resolution and export bundles expire after 7 days.
