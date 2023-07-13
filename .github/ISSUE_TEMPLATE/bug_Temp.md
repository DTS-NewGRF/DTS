---
name: "[버그사항]"
about: 버그사항 접수시 활용
title: "[버그] 버그사항"
labels: bug
assignees: octocat
body:
  - type: markdown
    attributes:
      value: |
        버그를 제보해주셔서 감사합니다.!
    - type: textarea
    id: expected
    attributes:
        description: Describe in a few words what you expected to happen.
    validations:
      required: true
  - type: textarea
    id: actual
    attributes:
        description: Describe in a few words what actually happens.
    validations:
      required: true
  - type: textarea
    id: reproduce
    attributes:
        description: As detailed as possible, please tell us how we can reproduce this. Feel free to attach a savegame (zip it first) to make it more clear.
      placeholder: |
        1. Loaded the attached savegame.
        2. Click on the button left of that other icon.
        3. The window doesn't open.
    validations:
      required: true

---

==========[버그내용]==========

==========[개선사항]==========

==========[DTS내용]==========
DTS 열차 이름 : 
도색 이름 : (미도색시 무시)
