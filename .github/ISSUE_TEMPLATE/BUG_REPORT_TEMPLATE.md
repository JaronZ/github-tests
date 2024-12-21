name: Bug Report
description: Create an issue for reporting a bug or unexpected behavior.
labels: bug

body:
  - type: markdown
    attributes:
      value: |
        ## Issue Title
        <!-- Provide a short title summarizing the issue -->
  - type: textarea
    attributes:
      label: Description
      description: A clear and concise description of what the issue is.
      placeholder: "Please describe the bug in detail."

  - type: textarea
    attributes:
      label: Steps to Reproduce
      description: Provide the steps to reproduce the issue. Include relevant environment details (device type, OS, etc.).
      placeholder: |
        1. Step one
        2. Step two
        3. Step three
  - type: textarea
    attributes:
      label: Expected Behavior
      description: Describe what you expected the app to do.
      placeholder: "What should have happened?"

  - type: textarea
    attributes:
      label: Actual Behavior
      description: Describe what actually happened.
      placeholder: "What actually happened?"

  - type: textarea
    attributes:
      label: Screenshots
      description: Add screenshots if relevant to help explain your problem.
      placeholder: "Attach screenshots here."

  - type: input
    attributes:
      label: Device Information
      description: Provide the device and OS details.
      placeholder: |
        - Device: iPhone 13
        - OS Version: iOS 17.0.3
  - type: textarea
    attributes:
      label: Additional Information
      description: Any other information that might be relevant.
      placeholder: "Add any extra context here."
