name: "🐞 Bug Report"
description: "Create a report to help us improve"
title: "BUG:"
labels: [Bug, Needs Triage]
body:
  - type: checkboxes
    attributes:
      label: "Is there an existing issue for this?"
      description: "Please search to see if an issue already exists for the bug you encountered."
      options:
        - label: "I have searched the existing issues"
          required: true
  - type: textarea
    attributes:
      label: "What happened?"
      description: "A concise description of what you're experiencing."
    validations:
      required: true
  - type: textarea
    attributes:
      label: "Add ScreenShots"
      description: "Add sufficient SS to explain your issue."
    validations:
      required: true
