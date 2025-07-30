---
name: Custom issue template
about: Describe this issue template's purpose here.
title: ''
labels: ''
assignees: emilbowry
body:
- type: dropdown
  id: download
  attributes:
    label: How did you download the software?
    options:
      - Homebrew
      - MacPorts
      - apt-get
      - Built from source
  validations:
    required: true
  
---


