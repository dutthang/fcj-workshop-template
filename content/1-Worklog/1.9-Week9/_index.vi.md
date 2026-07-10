---
title: "Worklog Tuần 9"
date: 2026-06-15
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---

### Mục tiêu tuần 9:

- Chạy thử nghiệm đánh giá Prototype, tiến hành kiểm thử tải (Stress Testing) hệ thống.
- Đóng gói mã nguồn và chuẩn bị sẵn sàng kiến trúc hạ tầng mạng mạng trên môi trường Cloud.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc                                                      | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu               |
| --- | -------------------------------------------------------------- | ------------ | --------------- | ---------------------------- |
| 2   | - Chạy thử nghiệm kịch bản người dùng cuối trên Prototype      | 15/06/2026   | 15/06/2026      | Kịch bản kiểm thử End-to-End |
| 3   | - Sử dụng công cụ chuyên dụng thực hiện Stress Testing các API | 16/06/2026   | 16/06/2026      | Apache JMeter / Locust Tools |
| 4   | - Phân tích các điểm nghẽn hệ thống và tinh chỉnh tài nguyên   | 17/06/2026   | 17/06/2026      | Biểu đồ log kiểm thử         |
| 5   | - Khởi tạo hạ tầng mạng (VPC, Subnet, Route Table) trên AWS    | 18/06/2026   | 18/06/2026      | AWS VPC Console              |
| 6   | - Đóng gói hoàn chỉnh ứng dụng Smart Food thành file deploy    | 19/06/2026   | 19/06/2026      | Maven Build Tools            |

### Kết quả đạt được tuần 9:

- Xác định được giới hạn chịu tải của hệ thống Backend (chỉ số CPS/TPS) thông qua các bài kiểm thử tải chuyên sâu.
- Khắc phục thành công các điểm nghẽn kết nối database phát hiện trong quá trình stress test.
- Thiết lập hoàn chỉnh phân vùng mạng cô lập an toàn (VPC, Public/Private Subnet) trên tài khoản Cloud AWS.
- Mã nguồn dự án Smart Food được đóng gói thành công thành các tệp triển khai tiêu chuẩn.
