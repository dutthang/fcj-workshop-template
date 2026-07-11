---
title: "Worklog Tuần 7"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.7. </b> "
---

### Mục tiêu tuần 7:

- Tích hợp công nghệ hiển thị 3D trên trình duyệt.
- Cập nhật schema SQL để lưu trữ metadata của các file tải lên S3.
- Xử lý giao diện luồng upload sản phẩm số.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc                                                                            | Ngày bắt đầu | Ngày hoàn thành |
| --- | ------------------------------------------------------------------------------------ | ------------ | --------------- |
| 2   | - Nghiên cứu thư viện Three.js để render trực tiếp mô hình 3D (file GLB).            | 01/06/2026   | 01/06/2026      |
| 3   | - Tích hợp 3D Viewer vào trang Chi tiết sản phẩm.                                    | 02/06/2026   | 02/06/2026      |
| 4   | - Cập nhật schema SQL để lưu metadata của file: đường dẫn S3, kích thước, định dạng. | 03/06/2026   | 03/06/2026      |
| 5   | - Hoàn thiện UI form upload hỗ trợ kéo thả nhiều định dạng file (PDF, GLB, Image).   | 04/06/2026   | 04/06/2026      |
| 6   | - Kiểm thử luồng nhập liệu form -> gọi API Backend -> lưu metadata xuống Database.   | 05/06/2026   | 05/06/2026      |

### Kết quả đạt được tuần 7:

- Chức năng xem trước (preview) mô hình 3D hoạt động mượt mà trên UI.
- Database đã có cấu trúc lưu trữ chuẩn xác cho các file tài nguyên liên kết với S3.
