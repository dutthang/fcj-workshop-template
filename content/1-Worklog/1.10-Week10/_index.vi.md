---
title: "Worklog Tuần 10"
date: 2024-01-01
weight: 2
chapter: false
pre: " <b> 1.10. </b> "
---

### Mục tiêu tuần 10:

- Xây dựng luồng Thư viện cá nhân (Library) để người dùng tải file.
- Xử lý phân quyền bảo mật Frontend (JWT).
- Chuẩn bị dữ liệu SQL an toàn để đưa lên Amazon RDS.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc                                                                            | Ngày bắt đầu | Ngày hoàn thành |
| --- | ------------------------------------------------------------------------------------ | ------------ | --------------- |
| 2   | - Code giao diện Thư viện cá nhân và tích hợp luồng download file an toàn.           | 22/06/2026   | 22/06/2026      |
| 3   | - Cấu hình Axios Interceptors tự động gắn JWT Token vào header cho các API bảo mật.  | 23/06/2026   | 23/06/2026      |
| 4   | - Viết script `seed-required.js` sử dụng lệnh UPSERT an toàn để deploy lên RDS.      | 24/06/2026   | 24/06/2026      |
| 5   | - Thực thi SQL trực tiếp để gán quyền Admin phục vụ việc test trên môi trường cloud. | 25/06/2026   | 25/06/2026      |
| 6   | - Thay đổi Base URL API trên Frontend chuẩn bị kết nối với backend chạy trên EC2.    | 26/06/2026   | 26/06/2026      |

### Kết quả đạt được tuần 10:

- Frontend xử lý bảo mật JWT chuẩn xác, gọi API yêu cầu xác thực thành công.
- Dữ liệu mẫu an toàn (không ghi đè data thật) đã sẵn sàng để migrate lên Amazon RDS.
