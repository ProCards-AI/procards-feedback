name: Bug report
description: Report something broken in ProCards.
title: '[Bug]: '
labels:
  - bug
body:
  - type: markdown
    attributes:
      value: |
        Thanks for reporting this. Please give enough detail for us to reproduce the issue quickly.

  - type: textarea
    id: summary
    attributes:
      label: What happened?
      description: Describe the bug clearly and include what you were trying to do.
      placeholder: When I open Portfolio and switch to All, the x-axis labels overlap on Android.
    validations:
      required: true

  - type: textarea
    id: expected
    attributes:
      label: What did you expect to happen?
      placeholder: The chart labels should space themselves without overlapping.
    validations:
      required: true

  - type: textarea
    id: steps
    attributes:
      label: Steps to reproduce
      description: List exact steps so we can reproduce the issue.
      placeholder: |
        1. Open the app
        2. Go to Portfolio
        3. Switch range to All
        4. Observe the x-axis labels
    validations:
      required: true

  - type: dropdown
    id: platform
    attributes:
      label: Platform
      options:
        - iPhone / iOS
        - Android
        - Web
        - Other / Unknown
    validations:
      required: true

  - type: input
    id: device
    attributes:
      label: Device model
      description: For example, iPhone 15 Pro, Pixel 8, Galaxy S24.
      placeholder: Pixel 8

  - type: input
    id: app_version
    attributes:
      label: App version
      description: Include the app version or build number if you know it.
      placeholder: 1.0.0 (123)

  - type: textarea
    id: screenshots
    attributes:
      label: Screenshots or screen recordings
      description: Drag images into the issue or paste links here.
      placeholder: Add screenshots, videos, or links here.

  - type: textarea
    id: extra_context
    attributes:
      label: Anything else?
      description: Include network conditions, account state, or anything else that might matter.
      placeholder: This only happens when Dynamic Type is set to Large.
