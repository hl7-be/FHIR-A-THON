---
name: Issue
about: Capturing issues across projects
title: Please type a title for the issue
body:
  - type: input
    id: title
    attributes:
      label: Title
      description: "Provide a brief and descriptive title for the issue."
      placeholder: "Enter the issue title here"
    validations:
      required: true

  - type: dropdown
    id: project
    attributes:
      label: Project
      description: "Select the project this issue is related to."
      multiple: true
      options:
        - A
        - B
        - C
    validations:
      required: true

  - type: markdown
    id: issue-text
    attributes:
      label: Issue Description
      description: "Describe the issue in detail. Use Markdown for formatting."
      placeholder: "Provide a detailed description of the issue here."
    validations:
      required: true
---



