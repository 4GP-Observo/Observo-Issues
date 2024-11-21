name: Bug Report
title: "[Observo] - Brief title of the issue"
description: Create an issue report for your bug report
body:
  - type: markdown
    attributes:
      value: >-
        Please provide a detailed description description of the issue you're
        experiencing. 

        This will help us resolve it as quickly as possible
  - type: dropdown
    id: dropdown-1
    attributes:
      options:
        - Developers
        - Support Team
        - Billing Team
      label: Department
      description: Which team you think will be fit to handle the issue.
      default: 0
  - type: textarea
    id: textarea-2
    attributes:
      value: Explain what went wrong, steps on how to reproduce the issue, how many
        times you have encountered this is, etc.
      label: Bug Description
      description: Describe the issue your facing in as much detail as possible.
