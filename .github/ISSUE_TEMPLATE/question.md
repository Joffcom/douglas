name: "❓ Question"
description: Create a new ticket for a new feature request
title: "❓ [QUESTION] - <title>"
labels: [
  "question"
]
body:
  - type: textarea
    id: question
    attributes:
      label: "Question"
      description: What your question
    validations:
      required: true