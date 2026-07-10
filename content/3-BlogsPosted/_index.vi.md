---
title: "Các bài blogs đã đăng"
date: 2024-01-01
weight: 3
chapter: false
pre: " <b> 3. </b> "
---

Tại đây sẽ là phần liệt kê, giới thiệu các blogs mà các bạn đã đăng trên [AWS Study Group](https://www.facebook.com/groups/awsstudygroupfcj). Ví dụ:

### [Blog 1 - THEO DÕI VÀ QUẢN LÝ CHI PHÍ CLAUDE CODE TRÊN AMAZON BEDROCK: GIẢI PHÁP TOÀN DIỆN CHO DEVELOPER](3.1-Blog1/)

Blog này cung cấp giải pháp toàn diện để giám sát mức độ sử dụng, kiểm soát chi phí và đo lường hiệu suất sinh code thực tế của Claude Code trên Amazon Bedrock thông qua OpenTelemetry và CloudWatch. Bài viết hướng dẫn chi tiết hai lựa chọn kiến trúc triển khai là Sidecar (tiết kiệm, gọn nhẹ) và Central (tập trung, dành cho Enterprise), giúp thu thập các dữ liệu quan trọng như lượng token tiêu thụ, số dòng code và hành vi của lập trình viên. Bên cạnh đó, giải pháp còn tích hợp bảng điều khiển trực quan PromQL, cơ chế quản lý ngân sách (Quota) tự động bằng AWS Lambda và khả năng phân tích dữ liệu lịch sử chuyên sâu với AWS Athena.

### [Blog 2 - TỔNG HỢP NHANH AWS WEEKLY: CLAUDE OPUS 4.8, AURORA MYSQL + KIRO, AWS TRANSFORM VÀ NHIỀU CẬP NHẬT ĐÁNG CHÚ Ý](3.2-Blog2/)

Blog này tổng hợp các cập nhật nổi bật mới nhất từ AWS, bao gồm việc tích hợp mô hình Claude Opus 4.8 mạnh mẽ lên Amazon Bedrock để hỗ trợ lập trình và suy luận. Ngoài ra, bài viết còn điểm qua các bản nâng cấp quan trọng như AWS Resilience Hub giúp đánh giá và quản lý khả năng phục hồi hệ thống, AWS Transform hỗ trợ ước tính TCO trước khi migrate, và sự kết hợp giữa Aurora MySQL với Kiro Powers cho phép quản trị cơ sở dữ liệu bằng ngôn ngữ tự nhiên.

### [Blog 3 - TÌM HIỂU CÁCH AMAZON COGNITO TỰ ĐỘNG ĐỒNG BỘ DỮ LIỆU XÁC THỰC GIỮA CÁC REGION](3.3-Blog3/)

Blog này giới thiệu tính năng Multi-Region Replication cho Amazon Cognito. Tính năng này cho phép tự động đồng bộ dữ liệu xác thực (bao gồm hồ sơ người dùng và thông tin đăng nhập) từ Region chính sang Region dự phòng. Việc áp dụng giải pháp này giúp giảm đáng kể công sức xây dựng cơ chế dự phòng, tăng khả năng sẵn sàng (High Availability) cho hệ thống và đảm bảo trải nghiệm đăng nhập liền mạch cho người dùng ngay cả khi xảy ra sự cố hạ tầng.
