---
title: "Sự kiện 2: FCAJ Community Day - 2026/05/23"
date: 23-05-2026
weight: 2
chapter: false
pre: " <b> 4.2. </b> "
---
![Proof](/fcj-workshop/images/4-EventParticipated/23052026.jpg)
### **1. Diễn giả 1 (Nguyen Gia Hung): Xu hướng thị trường lao động và sức mạnh của nền tảng kiến thức**

*   **Những nội dung chính:**
    *   **Nghịch lý của AI:** Khi AI giúp giảm chi phí phát triển phần mềm, nhu cầu sử dụng phần mềm lại tiếp tục tăng mạnh. Điều này tạo ra nhiều cơ hội nghề nghiệp mới, trong đó có việc bảo trì và cải tiến các đoạn mã do AI tạo ra.
    *   **Kỳ vọng mới từ thị trường:** Một sản phẩm chỉ dừng lại ở mức demo là chưa đủ. Sinh viên nên hướng đến việc xây dựng các sản phẩm thực tế có khả năng giải quyết những vấn đề cụ thể trong doanh nghiệp, chẳng hạn như các nghiệp vụ trong lĩnh vực ngân hàng.
    *   **Giá trị lâu dài:** Bằng đại học và kiến thức nền tảng vẫn giữ vai trò quan trọng khi cạnh tranh trong môi trường toàn cầu. AI nên được xem là một công cụ khuếch đại năng lực của những người đã có nền tảng tốt.

### **2. Diễn giả 2 (Tinh Truong): Context Is Everything - Giúp AI thực sự hoạt động hiệu quả**

*   **Những nội dung chính:**
    *   **Vấn đề "Internet Buller":** Việc sao chép code trực tiếp từ internet hoặc AI mà không hiểu rõ bối cảnh có thể tạo ra những hệ thống rời rạc, không phù hợp với tiêu chuẩn kỹ thuật và quy trình phát triển của doanh nghiệp.
    *   **Cung cấp đúng ngữ cảnh:** Để nhận được kết quả chính xác hơn, cần cung cấp cho AI những thông tin chuyên biệt theo từng lĩnh vực (domain-specific) thay vì chỉ sử dụng những kiến thức chung đã có sẵn trên internet.
    *   **Tư duy và khả năng ứng dụng AI:** Người học nên tìm hiểu cách các công ty hàng đầu tích hợp AI vào quy trình làm việc thực tế, thay vì chỉ sử dụng AI để giải bài tập hoặc tạo ra những đoạn code đơn giản.

### **3. Diễn giả 3 (Pham Nguyen Hai Anh): GenAI-Powered Auto Audit cho AWS Workload**

*   **Những nội dung chính:**
    *   **Agent là gì?:** Agent có thể được hiểu là sự kết hợp giữa **bộ não LLM** và **các công cụ, hành động mở rộng**. Khác với chatbot thông thường, Agent có thể thực hiện những hành động thực tế như đặt lịch hoặc gửi email.
    *   **Amazon QuickSight:** Công cụ này giúp những người không chuyên về kỹ thuật có thể khai thác dữ liệu và tạo báo cáo từ các nguồn như file Excel bằng cách tương tác với hệ thống thông qua ngôn ngữ tự nhiên.

### **4. Diễn giả 4 (Nguyen Tuan Thinh): CloudFront as Your Foundation**

*   **Những nội dung chính:**
    *   **Flat-Rate Pricing:** Cơ chế tính phí mới giúp doanh nghiệp hạn chế rủi ro phát sinh hóa đơn bất ngờ do các cuộc tấn công DDoS hoặc lưu lượng truy cập tăng đột biến.
    *   **Cải thiện hiệu năng:** Nhờ tận dụng hệ thống backbone cáp quang nội bộ của AWS cùng giao thức HTTP/3, CloudFront có thể cải thiện đáng kể tốc độ tải trang. Trong phần trình bày, mức cải thiện được đề cập là giảm tới 81% thời gian tải.
    *   **Bảo mật tại Edge:** Buổi chia sẻ giới thiệu mTLS (Mutual TLS) dành cho các ứng dụng yêu cầu xác thực hai chiều, cùng với VPC Origin giúp hạn chế việc để lộ trực tiếp hạ tầng backend ra internet.

### **5. Diễn giả 5 (UTMorpho): Building UTMorpho from Idea to Reality - 36 Hours with LotusHacks**

*   **Những nội dung chính:**
    *   **Dự án UTMorpho:** UTMorpho là một công cụ chỉnh sửa giao diện bằng AI, cho phép người dùng tương tác trực tiếp với các thành phần trên UI thay vì phải tạo lại toàn bộ giao diện từ đầu.
    *   **Kiến trúc Multi-Agent:** Hệ thống sử dụng ba Agent chuyên biệt: **Vision** để phân tích hình ảnh, **Layout** để xác định cấu trúc giao diện và **Design** để tạo ra phần code tương ứng.
    *   **Bài học thực tế:** Dự án cho thấy cách xử lý giới hạn token, hạn chế tình trạng AI tạo ra quá nhiều nội dung không cần thiết và duy trì sự tập trung vào các tính năng cốt lõi của MVP.

### **6. Diễn giả 6 (Duc Dao): Tính không xác định của các thiết lập LLM "xác định"**

*   **Những nội dung chính:**
    *   **Nền tảng xác suất:** LLM tạo văn bản bằng cách dự đoán token tiếp theo dựa trên các phân phối xác suất và giá trị logits.
    *   **Optimization Bias:** Các nhà cung cấp như OpenAI và AWS có thể gộp nhiều prompt để tối ưu việc sử dụng GPU. Vì vậy, kết quả trả về vẫn có thể thay đổi ngay cả khi tham số Temperature được đặt bằng 0.
    *   **Các chiến lược đề xuất:** JSON Mode có thể được sử dụng để tạo ra kết quả có cấu trúc ổn định hơn. Trong những trường hợp cần kiểm soát tối đa, có thể cân nhắc tự host model. Dù sử dụng phương án nào, hệ thống vẫn cần được thiết kế để có thể xử lý các phản hồi bất ngờ từ AI.

### **7. Diễn giả 7 (Vy Lam): Enterprise-Grade Multi-Agent System**

*   **Những nội dung chính:**
    *   **Giải quyết bài toán thực tế:** Các startup có thể không sở hữu đầy đủ báo cáo tài chính trong ba năm. Hệ thống AI có thể hỗ trợ quá trình đánh giá bằng cách thu thập và phân tích nhiều khía cạnh khác nhau, bao gồm thị trường, đội ngũ sáng lập và tài sản trí tuệ.
    *   **Quản trị rủi ro và Guardrails:** Trong môi trường doanh nghiệp, bảo mật là một ưu tiên quan trọng. Agent cần được giới hạn trong những **boundary** rõ ràng, đồng thời phải duy trì **audit trail** để các quyết định của AI có thể được truy vết và kiểm tra lại.