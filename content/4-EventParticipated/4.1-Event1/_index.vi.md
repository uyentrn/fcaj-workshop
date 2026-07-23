---
title: "Event 1"
date: 2026-07-31
weight: 1
chapter: false
pre: " <b> 4.1. </b> "
---

# Bài thu hoạch “AWS Cloud & AI Mastery Workshop”

### Mục Đích Của Sự Kiện

- Hệ thống hóa kiến thức toàn diện về hạ tầng Cloud, bảo mật, quy trình phát triển phần mềm hiện đại và ứng dụng AI/ML trên hệ sinh thái AWS.  
- Thảo luận và phân tích các bài toán thực tế thông qua 6 chuyên đề chuyên sâu do các diễn giả và sinh viên trình bày.  
- Chia sẻ định hướng nghề nghiệp, kỹ năng mềm và phương pháp phát triển năng lực cá nhân trong ngành Cloud & DevOps.  
- Kết nối cộng đồng học thuật và thực thi dự án: Tạo không gian trao đổi giữa sinh viên, chuyên gia và các kỹ sư đến từ các doanh nghiệp lớn. 

### Danh Sách Diễn Giả

- **Lê Hoàng Gia Đại** (Final-year student at HUTECH University) — WAF + ML for Cyber Attack Detection.  
- **Bao Huynh** (Junior Cloud Native Developer - Endava Vietnam, Founder / Head Lab - ITea Lab) — Docker – A containerization technology.  
- **Trần Trung Vinh** (System Administrator at Central Retail Group) — From IT Helpdesk to Senior Sysadmin.  
- **Nguyễn Quốc Bảo** — Multiplayer in the Cloud: Connecting Godot Clients with AWS WebSockets.  
- **Trương Huy Phước** — The Art of Effective Teamwork.  
- **Việt Phát** (AI majoring at Swinburne University of Technology) — Build GraphRAG applications using Amazon Bedrock and Amazon Neptune. 

### Nội Dung Nổi Bật

#### WAF + Machine Learning phát hiện tấn công mạng

- Hạn chế của WAF truyền thống: Các quy tắc cố định (rule-based) khó chống lại các cuộc tấn công Zero-day, tấn công lại/giả mạo (hybrid/spoofing) và hành vi bất thường mới.  
- Giải pháp NIDS dựa trên ML: Sử dụng tập dữ liệu CSE-CIC-IDS2018 để huấn luyện mô hình Machine Learning (đặc biệt là LightGBM cho độ chính xác cao) nhằm phân tích hành vi lưu lượng mạng theo thời gian thực.  
- Tích hợp hạ tầng AWS: Kết hợp các dịch vụ AWS WAF, EC2, Lambda, S3, Kinesis Data Firehose, CloudWatch và Security Hub để tự động hóa việc cảnh báo và giám sát mối đe dọa. 

#### Kỹ thuật Containerization với Docker

- **So sánh Virtualization vs Containerization:**
* Virtual Machines (VM) tiêu tốn nhiều tài nguyên do chạy riêng từng Guest OS và khởi động chậm.  
* Container chia sẻ Host OS qua Docker Engine, khởi động tính bằng milisecond, kích thước gọn nhẹ và chạy nhất quán trên mọi môi trường.

- **Cấu trúc & Lệnh cốt lõi:**
* Mô hình Layered Image trong Dockerfile (mỗi lệnh tạo một layer và có cơ chế lưu cache).  
* Các nhóm lệnh quan trọng điều khiển lifecycle của Container, Network, Volume và Docker Compose. 

- **Use cases thực tế:** 
* Áp dụng trong pipelines CI/CD, kiến trúc Microservices, môi trường dev/test và hiện đại hóa ứng dụng cũ.

#### Lộ trình nghề nghiệp: Từ Helpdesk đến Senior Sysadmin / Cloud DevOps

- **Tư duy vận hành hệ thống (Operations Mindset):**
* **Prevent first — fix later:** Tự động hóa công việc lặp đi lặp lại, viết tài liệu/runbook kỹ lưỡng và triển khai giám sát trước khi sự cố xảy ra.  
* **Nguyên tắc cốt lõi:** "Never test in production" để bảo vệ độ tin cậy của hệ thống.  
- **Lộ trình chuyển đổi:** Nắm vững Linux & Networking $\rightarrow$ Xây dựng lab thực hành $\rightarrow$ Tư duy Cloud (AWS, Elastic Scaling) $\rightarrow$ Infrastructure as Code (Terraform) $\rightarrow$ Văn hóa DevOps (CI/CD, Docker).  
- **Bài học phỏng vấn & Sự nghiệp:** Sự chuẩn bị dựa trên kinh nghiệm thực tế (portfolio/projects) quan trọng hơn chỉ có bằng cấp suông. 

#### Game Multiplayer trên Cloud với AWS WebSockets & Godot

- **Lựa chọn kiến trúc mạng Game:** So sánh giữa UDP/ENet (latency thấp cho FPS), HTTP Polling (đơn giản nhưng latency cao) và WebSocket (giao tiếp hai chiều, phù hợp cho game theo lượt/chat/lobby).  
- **Hạ tầng AWS Serverless:** Kết hợp Godot Client với API Gateway WebSocket, AWS Lambda (xử lý logic kết nối, ghép trận) và Amazon DynamoDB (lưu trạng thái connectionId và phòng chơi).  
- **Thách thức & Giải pháp:** Xử lý hiện tượng GoneException (kết nối ngắt đột ngột), tối ưu chi phí Scan trên DynamoDB và chuyển đổi từ Stateless Lambda sang AWS GameLift khi cần máy chủ dedicated. 

#### Kỹ năng làm việc nhóm hiệu quả

- **4 Quy tắc vàng:** 
1. Clear & Shared Goals: Mục tiêu rõ ràng và đồng thuận.  
2. Right Person, Right Place: Phân công đúng người, đúng việc.  
3. Open Communication & Active Listening: Lắng nghe chủ động và giao tiếp cởi mở.  
4. Personal Accountability: Trách nhiệm cá nhân cao.  
- **Ứng dụng công cụ số:** Kết hợp Trello, ClickUp (quản lý dự án), Google Workspace, Slack và Discord để tăng hiệu suất làm việc nhóm.

#### Xây dựng ứng dụng GraphRAG với Amazon Bedrock & Neptune

- **Vấn đề của RAG truyền thống:** Hạn chế trong các câu hỏi đòi hỏi suy luận nhiều bước (Multi-hop Reasoning).  
- **Sức mạnh của GraphRAG:** Sử dụng Đồ thị tri thức (Knowledge Graph) để biểu diễn rõ ràng các mối quan hệ giữa các thực thể thông qua các cạnh (edges).  
- **Hai phương án triển khai trên AWS:** 
* **Fully Managed Route:** Dùng Amazon Bedrock Knowledge Bases (chia nhỏ text, trích xuất entity) kết hợp Amazon Neptune Analytics (lưu trữ và tìm kiếm đồ thị).  
* **Custom Route:** Sử dụng pipeline tự dựng với LlamaIndex kết hợp Amazon Neptune để truy vấn ngôn ngữ Cypher linh hoạt. 

### Những Gì Học Được

#### Tư Duy Thiết Kế

- **Operations & Security Mindset:** Chuyển từ tư duy phản ứng với sự cố sang phòng ngừa chủ động. Hiểu rằng bảo vệ ứng dụng không thể chỉ phụ thuộc vào WAF tĩnh mà phải kết hợp ML và giám sát tự động.  
- **Xây dựng năng lực cốt lõi:** Đi sâu vào 1–2 kỹ năng nền tảng (Linux, Networking) trước khi mở rộng ra các công nghệ Cloud/DevOps nâng cao. Tập trung xây dựng dự án thực tế thay vì chạy theo bằng cấp.  
- **Business & User Impact:** Dù làm hạ tầng, game hay AI, mục tiêu cuối cùng vẫn là tối ưu chi phí, hiệu năng và trải nghiệm của người dùng.

#### Kiến Trúc Kỹ Thuật

- **Containerization & Deployment:** Nắm rõ cách đóng gói ứng dụng với Docker, tối ưu hóa layer image để đảm bảo tính nhất quán từ môi trường Dev đến Production.  
- **Serverless Real-time Architecture:** Hiểu rõ cơ chế xây dựng các ứng dụng giao tiếp thời gian thực qua WebSockets, quản lý kết nối ngắt bất đồng bộ với AWS Lambda và DynamoDB.  
- **Kiến trúc GraphRAG:** Nắm được cách vượt qua giới hạn của RAG truyền thống bằng cách kết hợp Knowledge Graph và LLM trên hạ tầng Amazon Bedrock & Neptune.

#### Ứng Dụng Vào Công Việc & Dự Án Thực Tế

- **Tối ưu quy trình phát triển phần mềm:** Tích hợp Docker vào các project hiện tại để chuẩn hóa môi trường làm việc giữa các thành viên, loại bỏ lỗi "works on my machine".  
- **Thực hành triển khai Serverless:** Áp dụng mô hình API Gateway + Lambda + DynamoDB vào các dự án web/app cần tính năng thời gian thực hoặc xử lý sự kiện nhẹ.  
- **Áp dụng văn hóa DevOps & IaC:** Bắt đầu viết kịch bản tự động hóa cấu hình và quản lý tài nguyên hạ tầng bằng mã (Infrastructure as Code) thay vì thao tác thủ công.  
- **Nâng cao hiệu quả làm việc nhóm:** Sử dụng rõ ràng các quy tắc phân công công việc, giao tiếp minh bạch qua Slack/Discord và thiết lập mục tiêu chung theo kịch bản rõ ràng. 

### Trải nghiệm trong event

Tham gia workshop **“AWS Cloud & AI Mastery Workshop”** là một trải nghiệm rất bổ ích, giúp em có góc nhìn đa chiều từ lý thuyết hạ tầng, công nghệ container, kiến trúc phần mềm, AI nâng cao cho đến các bài học sự nghiệp thực tế.

#### Học hỏi từ các diễn giả có chuyên môn cao
- Nhận được những góc nhìn chân thực từ anh Trần Trung Vinh về hành trình vượt khó từ Helpdesk lên Sysadmin, kinh nghiệm làm Cloud Native từ anh Bao Huynh, cũng như các giải pháp kỹ thuật sáng tạo từ bạn Gia Đại, Quốc Bảo và Việt Phát.  

#### Trải nghiệm kỹ thuật thực tế
- Được quan sát trực tiếp các buổi Demo như: cơ chế ghép trận real-time trên Godot và DynamoDB, mô hình phân loại tấn công bằng LightGBM, hay cấu trúc lớp của Docker Image.  

#### Kết nối và trao đổi
- Workshop tạo cơ hội trao đổi trực tiếp với các anh chị đi trước trong ngành.

#### Bài học rút ra
- Hành trình chuyển đổi số và phát triển sự nghiệp đòi hỏi sự kiên trì: mỗi bước đi nhỏ (từ làm chủ Linux, viết Dockerfile đến dựng kịch bản CI/CD) đều tích lũy nên năng lực vững chắc.  
- Việc làm chủ kết hợp giữa kiến thức hạ tầng (Cloud/DevOps), mô hình lập trình (Serverless/WebSockets) và AI (GraphRAG) sẽ tạo ra lợi thế cạnh tranh rất lớn trong tương lai.  

#### Một số hình ảnh khi tham gia sự kiện
* Thêm các hình ảnh của các bạn tại đây

