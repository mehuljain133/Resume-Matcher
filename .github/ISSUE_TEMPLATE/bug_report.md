name: 🐞 Bug Report
about: Report a bug to help improve Resume Matcher
title: "[Bug]: "
labels: bug
assignees: ""

body:
  - type: markdown
    attributes:
      value: |
        ## 🐛 Bug Description
        <!-- Clearly and concisely describe the bug. What went wrong? -->
        A clear and concise description of the issue.

  - type: input
    id: steps_to_reproduce
    attributes:
      label: 🔁 Steps to Reproduce
      description: "List steps to reproduce the issue, in order"
      placeholder: |
        1. Go to '...'
        2. Click on '...'
        3. Select '...'
        4. Observe the error

  - type: input
    id: expected_behavior
    attributes:
      label: ✅ Expected Behavior
      description: "What should have happened instead?"
      placeholder: "Describe the expected behavior"

  - type: input
    id: actual_behavior
    attributes:
      label: ❌ Actual Behavior
      description: "What actually happened"
      placeholder: "Describe the unexpected behavior"

  - type: checkboxes
    id: reproducibility
    attributes:
      label: 🧪 Reproducibility
      options:
        - label: Happens every time
        - label: Happens sometimes
        - label: Happened once

  - type: textarea
    id: screenshots
    attributes:
      label: 📸 Screenshots / Recordings
      description: "Attach screenshots or screen recordings to illustrate the problem"
      placeholder: "Drag & drop images or videos here"

  - type: input
    id: desktop
    attributes:
      label: 🖥️ Desktop Environment
      description: "Operating system, browser, versions, Node/Python/Ollama if relevant"
      placeholder: "e.g. Windows 11, Chrome 122, Python 3.12, Ollama 0.6.7"

  - type: input
    id: mobile
    attributes:
      label: 📱 Mobile Environment
      description: "Device, OS, browser, version"
      placeholder: "e.g. iPhone 14, iOS 17, Safari 17"

  - type: input
    id: resume_context
    attributes:
      label: 📄 Resume / Job Description Context
      description: "Context about resume format and job description"
      placeholder: "e.g. PDF resume, LinkedIn job description, 2 pages"

  - type: textarea
    id: logs
    attributes:
      label: 🧠 Logs / Console Output
      description: "Any relevant logs or error messages"
      placeholder: "Paste logs here"

  - type: textarea
    id: workarounds
    attributes:
      label: 🚧 Workarounds
      description: "Any temporary fix or workaround"
      placeholder: "Describe if any"

  - type: textarea
    id: additional_context
    attributes:
      label: 📌 Additional Context
      description: "Anything else that might help reproduce or fix the issue"
      placeholder: "Add context, links, or observations here"

  - type: checkboxes
    id: contribution_check
    attributes:
      label: 🙌 Contribution Check
      options:
        - label: I searched existing issues to avoid duplicates
        - label: I can help fix this issue
        - label: I’m open to discussion or clarification

  - type: markdown
    attributes:
      value: "💙 **Thank you for helping improve Resume Matcher!** Your feedback helps us build the **VS Code for resumes** 🚀"
