---
name: FHIR-A-THON feedback
about: Use this form to capture issues, questions, suggestions about the profiles and their testing 
#title: Please type a title for the issue
body:
  - type: dropdown
    id: project
    attributes:
      label: Project
      description: "Select the project this issue is related to."
      multiple: true
      options:
        - "Lab"
        - "Vaccination"
        - "Allergy"
        - "Population Screening"
    validations:
      required: false
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
  - type: checkboxes
    id: terms
    attributes:
      label: CheckList
      description: By submitting this issue, you agree to follow our [Code of Conduct]()
      options:
        - label: I agree to follow this project's Code of Conduct
          required: true
  - type: dropdown
    id: _version
    attributes:
      label: Select Release Version
      options:
        - v2.0.2
        - v2.0.1
        - v2.0.0
        - v1.2.0-rc.2
        - v0.1.1
        - v0.1.0
    validations:
      required: true
---

