---
title: Revert {{ payload.issue.title }}
assignees: {{ payload.issue.assignee.login }}
labels: {{payload.issue.labels}}
---
Issue closed by: {{ payload.sender.login }}.
[Issue link]({{payload.issue.url}})

--

{{payload.issue.body}}
