---
schemaVersion: treeseed.knowledge-page/v2
id: feedback.screenshot-privacy
projectId: 4c520946-e4c3-460d-a50f-255b65c78451
bookRef:
  store: treedx
  model: book
  id: treeseed-feedback-and-support
  path: books/feedback-and-support.md
  revision: 1
  digest: sha256:f299eab796a35381e4ac5ef43b5305dc86bb3efe1f79fd832923035e9bd381f8
slug: screenshot-privacy
title: Screenshot capture and redaction
summary: Understand what the optional browser capture masks and how private
  images are retained.
status: published
visibility: authenticated
order: 50
groupIds:
  - attachment
  - capture
  - privacy
  - redact
  - screenshot
contributors: []
relatedBookIds: []
relatedKnowledgeIds:
  - feedback.submitting
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
  - admin.feedback.submit
routePatterns:
  - /app/*
resourceTypes:
  - feedback-attachment
actionIds: []
keywords:
  - screenshot
  - capture
  - redact
  - privacy
  - attachment
documentationUrls: []
---

Screenshot capture happens in your browser and includes the complete page, including content below the visible viewport and any help, dialog, or popover that is open when you capture it. On desktop, the image ends at the page edge beside the feedback panel, so the panel never covers or changes the recorded page.

Typed values in freeform form controls, editable content, and explicitly marked private regions are masked while ordinary navigation, labels, selectors, and non-sensitive page content remain visible. Embedded content that cannot be captured safely is marked unavailable rather than presented as a privacy redaction.

Always inspect the preview before sending. Select the thumbnail to open a larger, scrollable review and close it when you are finished. Capture never uploads automatically, and you can replace or remove it.

Screenshots are stored privately. They remain available while feedback is open and expire 90 days after resolution.
