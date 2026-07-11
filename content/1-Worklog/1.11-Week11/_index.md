---
title: "Week 11 Worklog"
date: 2024-01-01
weight: 2
chapter: false
pre: " <b> 1.11. </b> "
---

### Week 11 Objectives:

- Deploy the Frontend to Vercel.
- Configure Proxy/Rewrites to connect the Frontend (Vercel) to the Backend (EC2).
- Query and verify data integrity on Amazon RDS.

### Tasks to be carried out this week:

| Day | Task                                                                                                     | Start Date | Completion Date |
| --- | -------------------------------------------------------------------------------------------------------- | ---------- | --------------- |
| 2   | - Deploy the React/Vite build to Vercel.                                                                 | 06/29/2026 | 06/29/2026      |
| 3   | - Write the `vercel.json` configuration to fix 404 errors on page reload (SPA routing).                  | 06/30/2026 | 06/30/2026      |
| 4   | - Configure rewrites proxy to redirect `/api/*` requests from Vercel to the EC2 Backend IP.              | 07/01/2026 | 07/01/2026      |
| 5   | - Use database management tools to connect to Amazon RDS to verify data written from the live interface. | 07/02/2026 | 07/02/2026      |
| 6   | - Conduct E2E testing for the entire online system (Vercel Frontend -> EC2 Backend -> RDS/S3).           | 07/03/2026 | 07/03/2026      |

### Week 11 Achievements:

- The Frontend was successfully published; SPA routing and Mixed Content/CORS errors were completely fixed via rewrites.
- The data flow is seamless; the Database on RDS accurately records data from real users.
