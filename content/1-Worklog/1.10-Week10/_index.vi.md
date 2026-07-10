---
title: "Worklog Tuần 10"
date: 2026-06-22
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---

### Mục tiêu tuần 10:

- Tiến hành deploy chính thức dự án Smart Food lên EC2 kết hợp cấu hình Web Server Nginx.
- Bắt đầu tham gia hỗ trợ trưởng nhóm thực hiện các bài kiểm thử trên dự án chung DaiMarket.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc                                                           | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                       |
| --- | ------------------------------------------------------------------- | ------------ | --------------- | ------------------------------------ |
| 2   | - Khởi tạo instance EC2 Production, cài đặt Java Runtime            | 22/06/2026   | 22/06/2026      |                                      |
| 3   | - Cấu hình máy chủ Web Server Nginx làm Reverse Proxy               | 23/06/2026   | 23/06/2026      | Hướng dẫn cấu hình Nginx             |
| 4   | - Deploy dự án Smart Food lên EC2, trỏ Domain và kích hoạt HTTPS    | 24/06/2026   | 24/06/2026      | AWS EC2 / Nginx Console              |
| 5   | - Tiếp nhận tài liệu kiến trúc hệ thống DaiMarket từ trưởng nhóm    | 25/06/2026   | 25/06/2026      | Tài liệu thiết kế hệ thống DaiMarket |
| 6   | - Phối hợp chạy các kịch bản kiểm thử hệ thống DaiMarket trên Cloud | 26/06/2026   | 26/06/2026      | Kịch bản kiểm thử của nhóm           |

### Kết quả đạt được tuần 10:

- Dự án cá nhân Smart Food được triển khai thành công lên Cloud AWS thực tế, người dùng có thể truy cập qua domain an toàn với giao thức HTTPS.
- Cấu hình thành công Nginx để điều hướng yêu cầu (Request routing) một cách hiệu quả vào ứng dụng Backend.
- Hiểu rõ sơ đồ kiến trúc và luồng vận hành của hệ thống DaiMarket do trưởng nhóm quản lý.
- Đóng góp kết quả kiểm thử bước đầu, giúp phát hiện sớm một số lỗi cấu hình hạ tầng trên môi trường test của DaiMarket.
