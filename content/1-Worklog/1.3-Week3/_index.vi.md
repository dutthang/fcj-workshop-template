---
title: "Worklog Tuần 3"
date: 2026-05-04
weight: 3
chapter: false
pre: " <b> 1.3. </b> "
---

### Mục tiêu tuần 3:

- Thực hành chuyên sâu với các dịch vụ cốt lõi: EC2, S3, kết nối bảo mật SSH.
- Thử nghiệm triển khai ứng dụng mẫu áp dụng mô hình Compute – Storage – Security.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc                                                    | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------ | ------------ | --------------- | ----------------------------------------- |
| 2   | - Khởi tạo instance EC2 (Linux) và cấu hình Security Group   | 04/05/2026   | 04/05/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 3   | - Cấu hình Key Pair và thực hành kết nối SSH vào EC2         | 05/05/2026   | 05/05/2026      | Terminal / Cửa sổ dòng lệnh               |
| 4   | - Tạo S3 Bucket, thiết lập Bucket Policy cho lưu trữ dữ liệu | 06/05/2026   | 06/05/2026      | AWS S3 Documentation                      |
| 5   | - Triển khai một ứng dụng web mẫu cơ bản lên instance EC2    | 07/05/2026   | 07/05/2026      | GitHub Sample Repository                  |
| 6   | - Liên kết ứng dụng mẫu với S3 và đánh giá mức độ bảo mật    | 08/05/2026   | 08/05/2026      |                                           |

### Kết quả đạt được tuần 3:

- Tạo lập và quản trị thành công máy chủ ảo EC2, cấu hình luật tường lửa (Inbound/Outbound) chính xác.
- Sử dụng thành thạo SSH key để truy cập từ xa vào hệ thống Linux trên Cloud.
- Tạo vùng lưu trữ Amazon S3, cấu hình phân quyền truy cập công khai/nội bộ an toàn.
- Chạy thử nghiệm thành công ứng dụng mẫu kết hợp cả năng lực tính toán (EC2) và lưu trữ đối tượng (S3).
