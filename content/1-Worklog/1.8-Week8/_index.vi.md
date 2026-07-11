---
title: "Worklog Tuần 8"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.8. </b> "
---

### Mục tiêu tuần 8:

- Xây dựng giao diện trang thanh toán (Checkout).
- Xử lý Database log giao dịch và cập nhật trạng thái đơn hàng từ SePay webhook.
- Hoàn thiện trải nghiệm mua hàng.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc                                                                           | Ngày bắt đầu | Ngày hoàn thành |
| --- | ----------------------------------------------------------------------------------- | ------------ | --------------- |
| 2   | - Code giao diện màn hình Checkout (Giỏ hàng / Thanh toán).                         | 08/06/2026   | 08/06/2026      |
| 3   | - Hiển thị mã QR thanh toán SePay và logic polling trạng thái giao dịch trên UI.    | 09/06/2026   | 09/06/2026      |
| 4   | - Thiết kế bảng SQL lưu trữ log giao dịch webhook từ SePay.                         | 10/06/2026   | 10/06/2026      |
| 5   | - Viết truy vấn SQL cập nhật trạng thái đơn hàng (PENDING -> SUCCESS) an toàn.      | 11/06/2026   | 11/06/2026      |
| 6   | - Test toàn bộ luồng tạo đơn hàng, hiển thị QR và nhận cập nhật thanh toán trên UI. | 12/06/2026   | 12/06/2026      |

### Kết quả đạt được tuần 8:

- Giao diện thanh toán chuyên nghiệp, mã QR hiển thị và tự động cập nhật trạng thái tốt.
- Database xử lý cập nhật trạng thái đơn hàng an toàn, tránh lỗi race condition.
