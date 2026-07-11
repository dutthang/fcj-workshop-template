---
title: "Week 10 Worklog"
date: 2024-01-01
weight: 2
chapter: false
pre: " <b> 1.10. </b> "
---

### Week 10 Objectives:

- Build the Personal Library flow for users to download files.
- Handle Frontend security authorization (JWT).
- Prepare secure SQL data to migrate to Amazon RDS.

### Tasks to be carried out this week:

| Day | Task                                                                                          | Start Date | Completion Date |
| --- | --------------------------------------------------------------------------------------------- | ---------- | --------------- |
| 2   | - Code the Personal Library interface and integrate a secure file download flow.              | 06/22/2026 | 06/22/2026      |
| 3   | - Configure Axios Interceptors to automatically attach JWT Tokens to headers for secure APIs. | 06/23/2026 | 06/23/2026      |
| 4   | - Write a `seed-required.js` script using safe UPSERT commands to deploy to RDS.              | 06/24/2026 | 06/24/2026      |
| 5   | - Execute direct SQL to assign Admin privileges for testing on the cloud environment.         | 06/25/2026 | 06/25/2026      |
| 6   | - Change the API Base URL on the Frontend in preparation for connecting to the EC2 backend.   | 06/26/2026 | 06/26/2026      |

### Week 10 Achievements:

- The Frontend accurately handles JWT security, successfully calling authenticated APIs.
- Safe mock data (without overwriting real data) is ready to migrate to Amazon RDS.
