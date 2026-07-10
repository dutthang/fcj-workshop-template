---
title: "Worklog Tuần 7"
date: 2026-06-01
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---

### Mục tiêu tuần 7:

- Khám phá kiến trúc phi máy chủ (Serverless) bao gồm AWS Lambda và Amazon DynamoDB.
- Nghiên cứu phương án xử lý các kết nối, truyền tải dữ liệu theo thời gian thực (Real-time).

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc                                                     | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                |
| --- | ------------------------------------------------------------- | ------------ | --------------- | ----------------------------- |
| 2   | - Tìm hiểu kiến trúc Serverless và viết hàm thử nghiệm Lambda | 01/06/2026   | 01/06/2026      | AWS Lambda Developer Guide    |
| 3   | - Thiết lập bảng và truy vấn cơ bản trên hệ NoSQL DynamoDB    | 02/06/2026   | 02/06/2026      | Amazon DynamoDB Console       |
| 4   | - Tìm hiểu giải pháp kết nối Real-time (WebSocket / Gateway)  | 03/06/2026   | 03/06/2026      | AWS API Gateway Documentation |
| 5   | - Hiện thực luồng cập nhật trạng thái đơn hàng Real-time      | 04/06/2026   | 04/06/2026      |                               |
| 6   | - Thử nghiệm mô phỏng kết nối Real-time giữa client và server | 05/06/2026   | 05/06/2026      | Môi trường Sandbox            |

### Kết quả đạt được tuần 7:

- Nắm vững tư duy Serverless, tự xây dựng và kích hoạt thành công các hàm AWS Lambda cơ bản.
- Hiểu được cấu trúc lưu trữ dạng Key-Value của DynamoDB và cách tối ưu hóa khóa chính (Partition Key).
- Thiết lập thành công kênh truyền thông điệp Real-time, giúp cập nhật trạng thái chuẩn bị và giao hàng ngay lập tức lên giao diện ứng dụng mà không cần tải lại trang.
