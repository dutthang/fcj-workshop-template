---
title: "Worklog Tuần 9"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.9. </b> "
---

### Mục tiêu tuần 9:

- Kiểm thử toàn bộ Prototype (End-to-End).
- Xử lý lỗi hiển thị Responsive và các vấn đề liên quan đến toàn vẹn dữ liệu.
- Hoàn thiện giao diện Quản trị (Admin).

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc                                                                                       | Ngày bắt đầu | Ngày hoàn thành |
| --- | ----------------------------------------------------------------------------------------------- | ------------ | --------------- |
| 2   | - Fix các bug hiển thị UI trên thiết bị di động và tablet (Responsive).                         | 15/06/2026   | 15/06/2026      |
| 3   | - Hoàn thiện giao diện Admin: Bảng thống kê, nút thao tác Ban/Unban user.                       | 16/06/2026   | 16/06/2026      |
| 4   | - Kiểm tra và rà soát lại toàn bộ khóa ngoại (Foreign Key) trong PostgreSQL.                    | 17/06/2026   | 17/06/2026      |
| 5   | - Chuyển đổi logic SQL từ xóa cứng (Hard Delete) sang xóa mềm (Soft Delete) để tránh lỗi P2003. | 18/06/2026   | 18/06/2026      |
| 6   | - Rà soát toàn bộ luồng mua bán từ góc nhìn Buyer và luồng quản lý của Admin.                   | 19/06/2026   | 19/06/2026      |

### Kết quả đạt được tuần 9:

- Giao diện hoạt động trơn tru trên nhiều kích thước màn hình.
- Lỗi liên kết khóa ngoại khi xóa sản phẩm đã được giải quyết bằng cơ chế Soft Delete trong CSDL.
