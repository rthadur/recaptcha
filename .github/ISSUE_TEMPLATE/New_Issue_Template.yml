name: Coral Issue Template
description: Use this template to report any issue
body:
  - type: markdown
    attributes:
      value: |
        Thank you for taking the time to report a Coral issue.
  - type: textarea
    id: what-happened
    attributes:
      label: Description
      description: Please describe the current and expected behaviour, and attach all files/info needed to reproduce the issue if applicable.
#       placeholder: Describe the issue here!
#       value: "A bug happened!"
    validations:
      required: true
  - type: dropdown
    id: issue-type
    attributes:
      label: Issue Type
      description: What type of issue would you like to report?
      multiple: true
      options:
        - Bug
        - Build/Install
        - Performance
        - Support
        - Feature Request
        - Documentation Feature Request
        - Documentation Bug
        - Others
  - type: dropdown
    id: Operating-System
    attributes:
      label: Operating System
      description: What OS are you seeing the issue in? If you don't see your OS listed, please provide more details in the "Description" section above.
      multiple: true
      options:
        - Windows 10
        - Mendel Linux
        - Linux
        - Ubuntu
        - Mac OS
  - type: dropdown
    id: Hardware
    attributes:
      label: Coral Device
#       description: If option not avaialble, please specify in what happend section!
      multiple: true
      options:
        - Dev Board
        - USB Accelerator
        - Dev Board Mini
        - Mini PCIe
        - M.2 Accelerator A+E
        - M.2 Accelerator B+M
        - M.2 Accelerator with dual Edge TPU
        - SoM
        - Accelerator Module
        - Enviro Board
        - Coral Camera
  - type: dropdown
    id: External-Hardware
    attributes:
      label: Other Devices
      description: If you don't see your device listed, please provide more details in the "Description" section above.
      multiple: true
      options:
        - Raspberry Pi 3
        - Rapsberry Pi 4
  - type: dropdown
    id: version
    attributes:
      label: Programming Language
      description: What programming language are you using? If "other", please provide more details in the "Description" section above.
      multiple: true
      options:
        - C++
        - Python 3.5
        - Python 3.6
        - Python 3.7
        - Python 3.8
        - Python 3.9
        - Other
  - type: textarea
    id: logs
    attributes:
      label: Relevant Log Output
      description: Please copy and paste any relevant log output. This will be automatically formatted into code.
      render: shell
#   - type: checkboxes
#     id: terms
#     attributes:
#       label: Code of Conduct
#       description: By submitting this issue, you agree to follow our [Code of Conduct](https://example.com)
#       options:
#         - label: I agree to follow this project's Code of Conduct
#           required: true

