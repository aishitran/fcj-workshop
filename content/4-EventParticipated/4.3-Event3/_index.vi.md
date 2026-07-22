---
title: "Event 3: FCAJ Community Day - 27/06/2026 (Online)"
date: 27-06-2026
weight: 3
chapter: false
pre: " <b> 4.3. </b> "
----------------------

![Proof](/fcj-workshop/images/4-EventParticipated/form-fcaj.jpg)

### **1. Diễn giả 1 (Steve Tran): AgenticOps cho Cloud**

* **Độ phức tạp vận hành cloud ngày càng tăng:** Khi hệ thống phát triển từ **Microservices** sang các môi trường có yêu cầu **Observability** cao hơn, số lượng công cụ và tác vụ vận hành cũng tăng theo. Điều này tạo ra một **"Bức tường phức tạp" (Complexity Wall)**, đồng thời làm tăng nhu cầu về kỹ sư vận hành cloud cũng như thời gian cần thiết để xử lý sự cố (**MTTR**).

* **CloudThinker:** Một nền tảng AgenticOps dành cho doanh nghiệp, sử dụng các AI agent để quan sát môi trường cloud, phân tích tình trạng hệ thống và hỗ trợ xử lý các vấn đề vận hành.

  * Hỗ trợ ứng phó sự cố, các tác vụ liên quan đến bảo mật và tối ưu chi phí.
  * Cung cấp các agent chuyên biệt cho từng vai trò và tác vụ vận hành khác nhau.
  * Liên tục quan sát môi trường để thu thập ngữ cảnh và xác định hành động phù hợp.
  * Áp dụng **tối ưu ngữ cảnh (context optimization)** nhằm giảm bớt ngữ cảnh không cần thiết và kiểm soát chi phí trong hệ thống multi-agent.
  * Tuân theo chu trình vận hành **Detect → Resolve → Validate** (Phát hiện → Xử lý → Xác thực), trong đó các hành động quan trọng vẫn có thể cần con người phê duyệt và phải tuân thủ các yêu cầu SLA.

### **2. Diễn giả 2 (Trung Vu, Nghi Danh, Kiet Tran): Xây dựng Voice Agent (VA) ở quy mô lớn**

* **Speech-to-speech:** Công nghệ speech-to-speech hiện tại vẫn chưa thực sự sẵn sàng để triển khai rộng rãi trong môi trường production.

* **Cách tiếp cận thực tế:** Kết hợp **TTS (Text-to-Speech)** với các mô hình đã được fine-tune để tạo ra giọng nói tự nhiên hơn và trải nghiệm giao tiếp giống con người hơn.

* **Giảm độ trễ (latency):** Thực hiện **warm-up** mô hình trước khi xử lý request nhằm cải thiện thời gian phản hồi.

* **Observability cho Voice Agent:** Cần một hệ thống hoàn chỉnh gồm metrics, tracing và observability để theo dõi hành vi của mô hình, phát hiện vấn đề và hỗ trợ cải tiến liên tục.

### **3. Diễn giả 3 (Bao Phan, Nguyen Nguyen): AWS DevOps Agent**

* **Hạn chế của phương pháp ứng phó sự cố truyền thống:** Việc điều tra thủ công tốn nhiều thời gian và chi phí, trong khi **MTTD** và **MTTR** vẫn có thể ở mức cao. Ngữ cảnh quan trọng cũng có thể bị mất trong quá trình bàn giao giữa các nhóm.

* **AWS DevOps Agent:** Một AI agent được thiết kế để hỗ trợ tự động hóa việc điều tra và ứng phó sự cố, đồng thời chủ động đề xuất các biện pháp phòng ngừa sự cố tương tự trong tương lai.

* **Nguyên tắc cốt lõi:** Giải pháp tập trung vào **Context Learning, Control, Integration, Collaboration** và **Cost-effectiveness** (Học ngữ cảnh, Kiểm soát, Tích hợp, Cộng tác và Hiệu quả chi phí).

* **Vòng đời ứng phó sự cố:** Quy trình gồm **Triage → Investigation → Mitigation → Prevention** (Phân loại → Điều tra → Giảm thiểu → Phòng ngừa), bao gồm phân loại sự cố, điều tra, giảm thiểu tác động và phòng ngừa.

* **Môi trường phù hợp:** Giải pháp hoạt động hiệu quả hơn trong các hệ thống đã có observability trưởng thành, với logs, metrics và alarms được tổ chức tốt. AI agent có thể tóm tắt ngữ cảnh và đề xuất bước tiếp theo, trong khi con người vẫn chịu trách nhiệm xem xét, phê duyệt và đưa ra quyết định cuối cùng.

### **4. Diễn giả 4 (Truong Tran, Anh Minh): AI-Powered Productivity Workforce Planning cho Doanh nghiệp**

* **Thách thức trong HR truyền thống:** Các quy trình thủ công thường tốn nhiều thời gian, có thể bỏ sót nhân tài giá trị, và dễ phụ thuộc vào đánh giá chủ quan thay vì dữ liệu.

* **Vai trò của AI:** Giảm bớt các tác vụ sàng lọc và xử lý thủ công, hỗ trợ ra quyết định HR dựa trên dữ liệu, và giúp tập trung nhiều hơn vào phát triển nhân tài cũng như chiến lược nhân sự.

* **Amazon Quick Solutions:** Các công cụ như **Chat Agents, Research, QuickSight, Flows** và **Automate** hỗ trợ xử lý dữ liệu, tạo báo cáo, trực quan hóa dữ liệu và tự động hóa quy trình nhiều bước.

* **Các trường hợp sử dụng trong HR:** Kết nối dữ liệu → phân tích thông tin → tạo báo cáo và biểu đồ trực quan → đánh giá ứng viên → theo dõi các hành động tiếp theo.

* **Hỗ trợ tuyển dụng:** AI có thể tạo câu hỏi phỏng vấn dựa trên mục tiêu tuyển dụng, hỗ trợ đánh giá ứng viên, và đưa ra khuyến nghị để bộ phận HR tham khảo trong quá trình ra quyết định.

### **5. Diễn giả 5 (Toan Nguyen, Nghi Danh): Xây dựng Private MCP an toàn cho AWS Quick**

* **Amazon Quick và MCP:** Tổng quan về Amazon Quick và **Model Context Protocol (MCP)**, bao gồm vai trò của MCP trong việc kết nối các hệ thống AI với dịch vụ bên ngoài.

* **Thách thức từ public endpoint:** MCP connector mặc định yêu cầu **public endpoint**, điều này có thể khiến ngữ cảnh và log phải đi qua internet công cộng. Điều này làm tăng **bề mặt tấn công (attack surface)** và phát sinh thêm các vấn đề bảo mật.

* **Kết nối Private VPC:** Có thể sử dụng kiến trúc private MCP để giảm mức độ tiếp xúc với internet công cộng.

  * **Private Entry:** Loại bỏ sự phụ thuộc vào public endpoint.
  * **Private DNS:** Hostname chỉ được phân giải trong mạng nội bộ của VPC.
  * **Luồng traffic riêng tư:** Traffic đi theo đường **ENI → ALB → MCP**, giữ kết nối trong môi trường mạng riêng tư và giảm mức độ tiếp xúc với internet công cộng.