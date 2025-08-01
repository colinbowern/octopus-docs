---
layout: src/layouts/Default.astro
pubDate: 2025-07-16
modDate: 2025-07-16
title: List failed deployments
description: Quickly find all recent failed deployments to spot patterns and initiate root cause analysis.
navOrder: 100
capability: Troubleshooting
---

:::div{.info}
**🏷 Capability:** Troubleshooting
:::

Quickly find all recent failed deployments to spot patterns and initiate root cause analysis. Octopus AI Assistant requires the project name and environment name as additional context to process the request.

## 📝 Prompt

```
List all failed deployments in the last 7 days for "[project-name]" project and "[environment-name]" environment
```

## 💡 Tips for customizing

- Filter by project or environment
- Group by error type
- Include timestamps and users

## 📚 Further reading

- [Octopus documentation](https://octopus.com/docs)
- [Octopus best practices](https://octopus.com/docs/best-practices)
