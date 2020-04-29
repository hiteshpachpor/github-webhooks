---
title: Revert {{ payload.issue.title }}
assignees: {{ payload.sender.login }}
labels: revert-hack
---
Issue closed by: {{ payload.sender.login }}.
[Issue link]({{payload.issue.url}})

--

{{payload.issue.body}}
