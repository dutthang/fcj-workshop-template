---
title: "Worklog Week 11"
date: 2026-06-29
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---

### Objectives for Week 11:

- Coordinate closely with the team leader to integrate distributed services for the DaiMarket system.
- Participate in reviewing, troubleshooting, and fixing technical issues arising in the Production environment.

### Tasks to be implemented this week:

| Day | Task                                                           | Start Date | End Date   | Resource/Documentation                   |
| --- | -------------------------------------------------------------- | ---------- | ---------- | ---------------------------------------- |
| Mon | - Co-connect Frontend (Vercel) with DaiMarket EC2 API          | 29/06/2026 | 29/06/2026 | Vercel & AWS EC2 Logs                    |
| Tue | - Assist linking S3 product images and RDS permissions         | 30/06/2026 | 30/06/2026 | AWS RDS / S3 Access Control              |
| Wed | - Locate IAM Role permission errors & CORS conflicts           | 01/07/2026 | 01/07/2026 | Browser Developer Tools / AWS CloudWatch |
| Thu | - Collaborate with leader to fix Production system errors      | 02/07/2026 | 02/07/2026 |                                          |
| Fri | - Perform overall End-to-End integration testing for DaiMarket | 03/07/2026 | 03/07/2026 | Stable Production Environment            |

### Achievements for Week 11:

- Successfully integrated the Vercel-hosted frontend to seamlessly connect with API processing endpoints on DaiMarket's EC2.
- Accurately configured IAM Role permissions allowing API servers to safely read/write data to AWS RDS and S3 storage.
- Completely fixed Cross-Origin Resource Sharing (CORS) blocks and image permission errors in the Production environment.
- Ensured the entire buying, selling, and operational business flow of DaiMarket functioned synchronously and accurately.
