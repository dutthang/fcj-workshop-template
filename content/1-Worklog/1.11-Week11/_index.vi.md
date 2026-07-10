---
title: "Worklog Tuần 11"
date: 2026-06-29
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---

### Mục tiêu tuần 11:

- Phối hợp chặt chẽ cùng trưởng nhóm thực hiện tích hợp các dịch vụ phân tán cho hệ thống DaiMarket.
- Tham gia rà soát, xử lý và khắc phục các sự cố kỹ thuật phát sinh trên môi trường Production.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc                                                           | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                           |
| --- | ------------------------------------------------------------------- | ------------ | --------------- | ---------------------------------------- |
| 2   | - Phối hợp kết nối Frontend (Vercel) với hệ thống EC2 API DaiMarket | 29/06/2026   | 29/06/2026      | Vercel & AWS EC2 Logs                    |
| 3   | - Hỗ trợ liên kết lưu trữ ảnh sản phẩm sang S3 và phân quyền RDS    | 30/06/2026   | 30/06/2026      | AWS RDS / S3 Access Control              |
| 4   | - Định vị các lỗi phân quyền IAM Role và xung đột CORS trên Cloud   | 01/07/2026   | 01/07/2026      | Browser Developer Tools / AWS CloudWatch |
| 5   | - Cùng trưởng nhóm tiến hành sửa lỗi Production cho hệ thống        | 02/07/2026   | 02/07/2026      |                                          |
| 6   | - Kiểm thử tích hợp tổng thể (End-to-End) toàn bộ luồng DaiMarket   | 03/07/2026   | 03/07/2026      | Môi trường Production ổn định            |

### Kết quả đạt được tuần 11:

- Tích hợp thành công giao diện chạy trên Vercel kết nối mượt mà tới các đầu API xử lý trên EC2 của dự án DaiMarket.
- Cấu hình phân quyền IAM Role chuẩn xác cho phép máy chủ API đọc/ghi dữ liệu an toàn vào cơ sở dữ liệu AWS RDS và không gian lưu trữ S3.
- Khắc phục triệt để lỗi chặn chia sẻ tài nguyên cross-origin (CORS) và lỗi phân quyền hình ảnh trên môi trường Production.
- Đảm bảo toàn bộ luồng nghiệp vụ mua bán, vận hành của DaiMarket hoạt động đồng bộ, chính xác.
