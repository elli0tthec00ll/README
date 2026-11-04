body:
- type: dropdown
  id: download
  attributes:
    label: How did you download the software?
    options:
      - Built from source
      - Homebrew
      - MacPorts
      - apt-get
    default: 0
  validations:
    required: true
