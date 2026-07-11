---
title: "Worklog Tuần 11"
date: 2024-01-01
weight: 2
chapter: false
pre: " <b> 1.11. </b> "
---

### Mục tiêu tuần 11:

- Deploy Frontend lên Vercel.
- Cấu hình Proxy/Rewrites để kết nối Frontend (Vercel) với Backend (EC2).
- Truy xuất và kiểm tra tính toàn vẹn của dữ liệu trên Amazon RDS.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc                                                                                      | Ngày bắt đầu | Ngày hoàn thành |
| --- | ---------------------------------------------------------------------------------------------- | ------------ | --------------- |
| 2   | - Deploy bản build React/Vite lên Vercel.                                                      | 29/06/2026   | 29/06/2026      |
| 3   | - Viết cấu hình `vercel.json` để fix lỗi 404 khi tải lại trang (SPA routing).                  | 30/06/2026   | 30/06/2026      |
| 4   | - Cấu hình rewrites proxy chuyển hướng request `/api/*` từ Vercel về IP của Backend EC2.       | 01/07/2026   | 01/07/2026      |
| 5   | - Dùng công cụ quản trị kết nối vào Amazon RDS để kiểm tra dữ liệu được ghi từ giao diện thật. | 02/07/2026   | 02/07/2026      |
| 6   | - Kiểm thử E2E toàn bộ hệ thống online (Vercel Frontend -> EC2 Backend -> RDS/S3).             | 03/07/2026   | 03/07/2026      |

### Kết quả đạt được tuần 11:

- Frontend đã public thành công, các lỗi SPA routing và Mixed Content/CORS được fix triệt để thông qua rewrites.
- Luồng dữ liệu chạy xuyên suốt, Database trên RDS ghi nhận dữ liệu chính xác từ người dùng thực.
