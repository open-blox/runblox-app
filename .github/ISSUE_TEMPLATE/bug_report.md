---
name: Bug form
description: File a Issue report
title: "[BUG]: "
labels: ["help wanted"]
assignees: ''
body:
  - type: markdown
    attributes:
      value: |
        Thanks for taking the time to fill out this bug report!

        Please fill out the issue report form
  - type: dropdown
    id: os
    attributes:
      label: OS
      description: On which platform?
      options:
        - iOS
        - Android
    validations:
      required: true
  - type: input
    id: device_model
    attributes:
      label: Device Model
      description: On what model you are experiencing issues?
      placeholder: iPhone XR
    validations:
      required: true
  - type: input
    id: app_version
    attributes:
      label: RunBlox App version
      description: Which version you are experiencing issues?
      placeholder: 1.2.2.131
    validations:
      required: true
  - type: textarea
    id: what-happened
    attributes:
      label: What happened?
      description: Also tell us, what did you expect to happen?
      placeholder: Tell us what you see!
      value: |
        1. Go to '...'
        2. Click on '....'
        3. Scroll down to '....'
        4. See error
    validations:
      required: true
---

**Additional context**
Add any other context about the problem here.