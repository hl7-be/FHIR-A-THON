---
name: Issue
about: Use this form to capture issues, questions, suggestions about the profiles and their testing 
title: Please type a title for the issue
body:
  - type: dropdown
    id: project
    attributes:
      label: Project
      description: "Select the project this issue is related to."
      multiple: true
      options:
        - "Project A"
        - "Project B"
        - "Project C"
    validations:
      required: true

  - type: input
    id: title
    attributes:
      label: Title
      description: "Provide a brief and descriptive title for the issue."
      placeholder: "Enter the issue title here"
    validations:
      required: false

  - type: markdown
    id: issue-text
    attributes:
      label: Issue Description
      description: "Describe the issue in detail. Use Markdown for formatting."
      placeholder: "Provide a detailed description of the issue here."
    validations:
      required: true
---



