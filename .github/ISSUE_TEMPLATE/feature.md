name: 功能改进
description: Feature Request
title: "[Feature Request]: "
labels: ["feature request"]
body:
  - type: markdown
    attributes:
      value: |
        请说明你希望添加的功能。
  - type: input
    id: version
    attributes:
      label: 当前程序版本
      description: 目前使用的程序版本
    validations:
      required: true
  - type: textarea
    id: feature-request
    attributes:
      label: 功能改进
      description: 请详细描述需要改进或者添加的功能。
      placeholder: "功能改进"
    validations:
      required: true
  - type: textarea
    id: references
    attributes:
      label: 参考资料
      description: 可以列举一些参考资料，但是不要引用同类但商业化软件的任何内容。
      placeholder: "参考资料"