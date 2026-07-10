---
title: "Saturday Meet up"
date: 2026-06-12
weight: 1
chapter: false
pre: " <b> 4.2. </b> "
---

# Bài thu hoạch “Saturday Meet up”

### Mục Đích Của Sự Kiện

- Chia sẻ kiến thức và kinh nghiệm thực chiến trong đa dạng các lĩnh vực công nghệ: Cloud, Cyber Security, Game Networking, AI/GenAI và Containerization.
- Cung cấp góc nhìn thực tế về hành trình phát triển sự nghiệp từ các vị trí nền tảng (Helpdesk/Sysadmin) lên cấp độ Senior và Cloud/DevOps.
- Trau dồi kỹ năng mềm thiết yếu như kỹ năng làm việc nhóm (Teamwork) và tư duy vận hành hệ thống hạ tầng IT.

### Danh Sách Diễn Giả

- **Trương Huy Phước** - Trình bày về Nghệ thuật làm việc nhóm hiệu quả (The Art of Effective Teamwork).
- **Nguyễn Quốc Bảo** - Trình bày về Multiplayer in the Cloud (Godot + AWS WebSockets).
- **Lê Hoàng Gia Đại** - Trình bày về Hệ thống phát hiện xâm nhập mạng bằng Machine Learning trên AWS (NIDS).
- **Bảo Huỳnh** - Junior Cloud Native Developer tại Endava Vietnam, trình bày về Docker & Containerization.
- **Trần Trung Vinh** - System Administrator tại Central Retail Group, chia sẻ hành trình từ IT Helpdesk đến Senior Sysadmin.
- **Việt Phát** - Trình bày về ứng dụng GraphRAG với Amazon Bedrock và Amazon Neptune.

### Nội Dung Nổi Bật

#### Nghệ thuật làm việc nhóm hiệu quả (Effective Teamwork)

- **4 nguyên tắc vàng:** Mục tiêu rõ ràng và chung (Clear & Shared Goals), Đúng người đúng việc (Right Person, Right Place), Giao tiếp cởi mở và Lắng nghe tích cực, Trách nhiệm cá nhân.
- Tầm quan trọng của các công cụ hỗ trợ số (Trello, ClickUp, Slack, Discord) trong việc tối ưu hóa và đồng bộ hóa công việc của nhóm.

#### Multiplayer in the Cloud với Godot & AWS WebSockets

- Hướng dẫn xây dựng kiến trúc Serverless cho game multiplayer bằng **AWS API Gateway, AWS Lambda và Amazon DynamoDB**.
- So sánh lợi thế của WebSocket (phù hợp cho game turn-based/lobby) so với UDP hay HTTP Polling.
- Cách Godot Client tích hợp `WebSocketPeer` để gửi và nhận message qua WebSocket, xử lý matchmaking và cập nhật trạng thái game realtime.

#### Bảo mật với AWS WAF & Machine Learning NIDS

- Phân tích sự hạn chế của các hệ thống Firewall dựa trên rule truyền thống (Signature-based) trước các cuộc tấn công Zero-day hoặc hành vi dị thường.
- Kết hợp **AWS WAF** với mô hình **Machine Learning (NIDS)** để tăng cường khả năng phát hiện xâm nhập chủ động dựa trên dữ liệu mạng thực tế (sử dụng tập dữ liệu CSE-CIC-IDS2018).

#### Containerization với Docker

- Phân biệt giữa Virtualization (Máy ảo VM truyền thống) và Containerization. Container nhẹ hơn, chia sẻ host OS, khởi động nhanh tính bằng mili-giây và tốn ít tài nguyên hơn.
- Cấu trúc cơ bản: Dockerfile, Images và Containers. Tính ứng dụng cao trong CI/CD pipeline, kiến trúc Microservices và ứng dụng Cloud-native.

#### Hành trình sự nghiệp từ IT Helpdesk đến Senior Sysadmin

- Bài học thực tế: Đừng chỉ hỗ trợ hệ thống, hãy tìm hiểu cách nó được xây dựng. Nắm vững nền tảng Linux, Networking và tự xây dựng các môi trường thực hành (hands-on labs).
- **Mindset vận hành:** Luôn phòng ngừa trước khi sửa lỗi (Prevent first - fix later), tự động hóa các tác vụ lặp lại, và nguyên tắc tối thượng: "Không bao giờ test trực tiếp trên môi trường Production".

#### GenAI: Xây dựng ứng dụng GraphRAG

- RAG truyền thống thường gặp khó khăn trong việc suy luận các mối liên hệ phức tạp. GraphRAG giải quyết bằng khả năng "Multi-hop Reasoning".
- Giới thiệu kiến trúc tích hợp giữa **Amazon Bedrock** (LLM, Embeddings) và **Amazon Neptune** (Graph Database) để lưu trữ các nodes/edges và truy vấn tri thức dạng đồ thị.

### Những Gì Học Được

#### Tư Duy Kỹ Thuật & Kiến Trúc

- Hiểu rõ sự dịch chuyển từ hạ tầng On-Premise nguyên khối sang Cloud, và từ Máy ảo (VM) sang kiến trúc Container (Docker) / Serverless hiện đại.
- Nhận thức được vai trò của AI/ML không chỉ ở chatbot mà còn trong việc tự động hóa bảo mật (Security ML-based) và nâng cao độ chính xác của hệ thống truy xuất thông tin (GraphRAG).

#### Kỹ Năng Mềm & Định Hướng Sự Nghiệp

- Kinh nghiệm thực tế (Practical experience) và Portfolio thông qua các dự án cá nhân giá trị hơn rất nhiều so với chỉ sưu tầm chứng chỉ. Đi sâu vào 1-2 kỹ năng cốt lõi trước khi mở rộng.
- Kỹ năng giao tiếp và làm việc nhóm là chìa khóa để dự án thành công. Áp dụng đúng 4 nguyên tắc vàng sẽ giúp team phối hợp nhịp nhàng, giảm thiểu xung đột.

### Ứng Dụng Vào Công Việc

- **Sử dụng Docker:** Bắt đầu đóng gói các ứng dụng/dự án nhỏ cá nhân bằng Dockerfile để môi trường dev đồng nhất và dễ dàng deploy.
- **Nâng cấp bảo mật đồ án:** Tìm hiểu thêm về WAF hoặc áp dụng tư duy của NIDS để theo dõi log và ngăn chặn các request xấu cho các ứng dụng web đang phát triển.
- **Thực hành Cloud & Game Dev:** Thử nghiệm xây dựng một mô hình client-server đơn giản dùng WebSockets (hoặc n8n kết nối API) như một bài thực hành làm quen với Serverless.
- **Cải thiện Teamwork:** Thiết lập rõ ràng mục tiêu và quy định dùng chung các công cụ quản lý (Trello/Slack) một cách bài bản hơn cho các đồ án nhóm trên trường.

### Trải nghiệm trong event

Tham gia sự kiện **"Saturday Meet up"** lần này mang lại cho tôi những góc nhìn vô cùng thực tế và đa chiều, kéo gần khoảng cách giữa giảng đường và yêu cầu thực tiễn của doanh nghiệp.

#### Sự đa dạng và thực chiến về công nghệ

- Các phiên trình bày bao phủ một phổ công nghệ rất rộng: từ Game Development, DevOps, Cloud Infrastructure, Security cho đến GenAI. Mỗi topic đều đi vào giải quyết bài toán hệ thống cụ thể chứ không hề lý thuyết suông.
- Việc được xem trực tiếp cách Godot kết nối với AWS Lambda hay xem Dashboard theo dõi tấn công mạng của NIDS giúp tôi hình dung rõ nét cách các kiến trúc này vận hành.

#### Cảm hứng từ những câu chuyện thực tế

- Phần chia sẻ về hành trình từ IT Helpdesk lên Senior Sysadmin thực sự truyền cảm hứng lớn. Câu chuyện này nhắc nhở tôi rằng xuất phát điểm không quan trọng bằng sự kiên trì đào sâu kiến thức nền tảng và tinh thần "keep going".

#### Xây dựng tư duy vận hành

- Tôi đặc biệt ấn tượng với quy tắc "Không bao giờ test trên Production". Điều này giúp tôi thay đổi thói quen làm code, cẩn thận hơn trong khâu testing và trân trọng sự ổn định (availability) của hệ thống.

#### Bài học rút ra

- Công nghệ liên tục ra mắt những phiên bản mới (như GenAI, GraphRAG), do đó việc nắm vững nền tảng cốt lõi (Networking, Linux, Database) và tự trang bị kỹ năng tự học là cách duy nhất để duy trì sức cạnh tranh.
- Sự thành công của dự án công nghệ không chỉ do code giỏi, mà phần lớn đến từ quy trình giao tiếp, khả năng chia sẻ tầm nhìn chung và nghệ thuật làm việc nhóm hiệu quả.

#### Một số hình ảnh khi tham gia sự kiện

- Thêm các hình ảnh của các bạn tại đây

> Nhìn chung, sự kiện là một bức tranh toàn cảnh về ngành công nghệ thông tin hiện đại. Sự kết hợp hài hòa giữa chuyên môn kỹ thuật sâu sắc (Cloud, AI, Docker) và định hướng tư duy làm nghề thực chiến chính là hành trang quý báu giúp tôi tự tin hơn trên con đường phát triển chuyên môn phía trước.
