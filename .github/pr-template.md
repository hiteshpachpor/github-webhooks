---
title: Revert {{ payload.pull_request.title }}
assignees: hiteshpachpor
labels: revert-hack
---
- Tagged by: @{{ payload.sender.login }}.
- [Link]({{payload.pull_request.html_url}})

---

{{payload.pull_request.body}}
