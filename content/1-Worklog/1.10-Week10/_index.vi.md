---
title: "Nhật Ký Tuần 10"
date: 2026-06-22
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---

### Mục tiêu Tuần 10:

* Xây dựng ứng dụng serverless hoàn chỉnh bằng AWS Lambda, API Gateway và các dịch vụ liên quan.
* Học các mẫu kiến trúc ứng dụng hiện đại (microservices, hướng sự kiện).
* Thành thạo xác thực và bảo mật cho ứng dụng serverless với Cognito.
* Triển khai pipeline CI/CD cho các bản triển khai serverless.
* Thiết lập giám sát và gỡ lỗi toàn diện cho ứng dụng serverless.
* Khám phá API GraphQL với AWS AppSync.

### Các nhiệm vụ thực hiện trong tuần:

| Chủ đề | Nhiệm vụ | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| --- | --- | --- | --- | --- |
| Nền tảng Serverless | **Serverless Bookstore: Bắt đầu với các hàm AWS Lambda** <br> - Tạo hàm Lambda cho logic nghiệp vụ cốt lõi <br> - Hiểu về môi trường thực thi Lambda <br> - Quản lý cấu hình hàm và biến môi trường <br> - Triển khai xử lý lỗi và ghi log phù hợp | 22/06/2026 | 22/06/2026 | <https://000078.awsstudygroup.com/> |
| Phát triển API | **Serverless - Xây dựng Frontend gọi API Gateway** <br> - Tạo endpoint REST API bằng API Gateway <br> - Cấu hình mô hình request/response <br> - Triển khai CORS cho các yêu cầu cross-origin <br> - Xây dựng ứng dụng frontend gọi API | 23/06/2026 | 23/06/2026 | <https://000079.awsstudygroup.com/> |
| Infrastructure as Code | **Serverless - Triển khai ứng dụng với SAM** <br> - Sử dụng Serverless Application Model (SAM) để định nghĩa hạ tầng <br> - Định nghĩa tài nguyên Lambda, API Gateway và dữ liệu <br> - Tự động hóa pipeline triển khai <br> - Quản lý cấu hình theo từng môi trường | 23/06/2026 | 23/06/2026 | <https://000080.awsstudygroup.com/> |
| Xác thực & Bảo mật | **Serverless - Xác thực với Amazon Cognito** <br> - Thiết lập Cognito User Pool để quản lý người dùng <br> - Triển khai kiểm tra token JWT <br> - Tích hợp Cognito với API Gateway <br> - Quản lý thuộc tính và quyền của người dùng | 24/06/2026 | 24/06/2026 | <https://000081.awsstudygroup.com/> |
| HTTPS & Bảo mật | **Serverless - Thiết lập SSL cho ứng dụng serverless** <br> - Cấu hình chứng chỉ SSL/TLS với ACM <br> - Thiết lập tên miền tùy chỉnh <br> - Triển khai bắt buộc HTTPS <br> - Cấu hình các header bảo mật | 25/06/2026 | 25/06/2026 | <https://000082.awsstudygroup.com/> |
| Xử lý Bất đồng bộ | **Serverless - Xử lý đơn hàng với SQS và SNS** <br> - Tạo hàng đợi SQS cho xử lý tách rời (decoupled) <br> - Gửi thông điệp đến các topic SNS <br> - Triển khai Lambda consumer cho luồng xử lý bất đồng bộ <br> - Xử lý gộp thông điệp theo lô và xử lý lỗi | 26/06/2026 | 26/06/2026 | <https://000083.awsstudygroup.com/> |
| CI/CD | **Serverless - CI/CD với AWS CodePipeline** <br> - Thiết kế pipeline CI/CD cho serverless <br> - Tích hợp giai đoạn quản lý mã nguồn và build <br> - Tự động hóa kiểm thử và triển khai <br> - Triển khai chiến lược rollback | 27/06/2026 | 27/06/2026 |<https://000084.awsstudygroup.com/> |
| Giám sát & Gỡ lỗi | **Serverless - Giám sát ứng dụng Serverless với CloudWatch và X-Ray** <br> - Cấu hình log và số liệu CloudWatch <br> - Theo dõi luồng thực thi Lambda bằng X-Ray <br> - Xác định các điểm nghẽn hiệu năng <br> - Thiết lập cảnh báo và dashboard | 28/06/2026 | 28/06/2026 | <https://000085.awsstudygroup.com/> |
| Phát triển API | **Serverless - Giới thiệu về AWS AppSync** <br> - Thiết kế schema GraphQL <br> - Kết nối nguồn dữ liệu với AppSync <br> - Triển khai resolver cho truy vấn và mutation <br> - Thiết lập subscription theo thời gian thực | 28/06/2026 | 28/06/2026 | <https://000086.awsstudygroup.com/> |

# Thành tựu Tuần 10

## Nền tảng Ứng dụng Serverless
- Tạo **các hàm Lambda** triển khai logic nghiệp vụ cho ứng dụng Bookstore.
- Hiểu về **môi trường thực thi Lambda**, hàm handler và các mô hình gọi hàm (invocation).
- Quản lý **cấu hình hàm** bao gồm bộ nhớ, timeout, biến môi trường và cài đặt VPC.
- Triển khai **xử lý lỗi và ghi log toàn diện** bằng CloudWatch Logs để phục vụ gỡ lỗi.

## Phát triển REST API
- Xây dựng **các endpoint REST API** bằng Amazon API Gateway theo kiến trúc dựa trên tài nguyên.
- Cấu hình **mô hình request/response**, kiểm tra dữ liệu và chuyển đổi dữ liệu.
- Triển khai header **CORS (Cross-Origin Resource Sharing)** để truy cập API từ trình duyệt một cách an toàn.
- Kết nối **ứng dụng frontend** với backend serverless để tạo trải nghiệm người dùng tương tác.

## Infrastructure as Code với SAM
- Định nghĩa **kiến trúc serverless hoàn chỉnh** bằng template AWS SAM (Serverless Application Model).
- Xác định **hàm Lambda, cấu hình API Gateway, tài nguyên cơ sở dữ liệu và quyền** dưới dạng YAML khai báo.
- Tự động hóa **triển khai SAM**, tạo stack CloudFormation và quản lý vòng đời tài nguyên.
- Quản lý **cấu hình theo từng môi trường** cho các bản triển khai development, staging và production.

## Xác thực Người dùng với Cognito
- Thiết lập **Amazon Cognito User Pool** để quản lý đăng ký, xác thực và định danh người dùng.
- Triển khai **kiểm tra token JWT (JSON Web Token)** trong API Gateway để truy cập API một cách an toàn.
- Tích hợp **xác thực Cognito** với ứng dụng serverless bằng các luồng OAuth 2.0.
- Quản lý **thuộc tính, nhóm và quyền của người dùng** để kiểm soát truy cập chi tiết.

## Cấu hình HTTPS & SSL
- Cấu hình **chứng chỉ AWS Certificate Manager (ACM)** cho kết nối HTTPS an toàn.
- Thiết lập **tên miền tùy chỉnh** ánh xạ đến endpoint API Gateway.
- Bắt buộc **HTTPS** và chuyển hướng lưu lượng HTTP, đảm bảo giao tiếp được mã hóa.
- Triển khai **các header bảo mật** (HSTS, X-Frame-Options, v.v.) để tăng cường bảo mật.

## Xử lý Bất đồng bộ
- Tạo **hàng đợi SQS (Simple Queue Service)** để tách rời các hàm Lambda và xử lý lưu lượng tăng đột biến.
- Gửi **thông điệp đến các topic SNS (Simple Notification Service)** cho mẫu nhắn tin fan-out.
- Triển khai **Lambda consumer** được kích hoạt bởi sự kiện SQS để xử lý đơn hàng bất đồng bộ.
- Xử lý **gộp thông điệp theo lô, visibility timeout và Dead-Letter Queue** để xử lý thông điệp một cách đáng tin cậy.

## Triển khai Pipeline CI/CD
- Thiết kế và triển khai **AWS CodePipeline** để tự động hóa triển khai ứng dụng serverless.
- Tích hợp các giai đoạn **quản lý mã nguồn (GitHub/CodeCommit), build (CodeBuild) và triển khai (CodeDeploy)**.
- Tự động hóa **kiểm thử** bao gồm unit test, integration test và quét bảo mật trong pipeline.
- Triển khai **chiến lược rollback** để phục hồi nhanh chóng khi có sự cố triển khai.

## Giám sát Toàn diện
- Cấu hình **CloudWatch Logs** để ghi log tập trung cho hàm Lambda và phục vụ gỡ lỗi.
- Sử dụng **CloudWatch Metrics và Alarms** để giám sát chủ động và phản ứng sự cố.
- Kích hoạt **AWS X-Ray tracing** để trực quan hóa luồng thực thi Lambda, xác định điểm nghẽn và hiểu các phụ thuộc dịch vụ.
- Tạo **dashboard vận hành** hiển thị tình trạng ứng dụng, hiệu năng và tỷ lệ lỗi theo thời gian thực.

## API GraphQL với AppSync
- Thiết kế **schema GraphQL** cho truy vấn API linh hoạt và hiệu quả.
- Kết nối **nhiều nguồn dữ liệu** (Lambda, RDS, DynamoDB, HTTP) với AppSync để có API thống nhất.
- Triển khai **resolver** chuyển đổi các thao tác GraphQL thành truy vấn nguồn dữ liệu.
- Thiết lập **subscription theo thời gian thực** để đẩy dữ liệu thay đổi đến các client đang kết nối.

### Tóm tắt lý thuyết
- **Lambda**: Dịch vụ tính toán serverless chạy mã để phản hồi sự kiện; lý tưởng để xây dựng ứng dụng có khả năng mở rộng, hướng sự kiện.
- **API Gateway**: Dịch vụ được quản lý hoàn toàn để tạo, xuất bản và quản lý REST API và WebSocket API.
- **SAM**: Ngôn ngữ template Infrastructure-as-Code giúp đơn giản hóa việc định nghĩa và triển khai ứng dụng serverless.
- **Cognito**: Dịch vụ quản lý định danh và truy cập người dùng cho phép xác thực và ủy quyền an toàn.
- **SQS/SNS**: Các dịch vụ dựa trên thông điệp cho phép giao tiếp bất đồng bộ, tách rời và có khả năng mở rộng.
- **X-Ray**: Dịch vụ tracing phân tán cung cấp khả năng quan sát luồng thực thi Lambda và các phụ thuộc dịch vụ.
- **AppSync**: Dịch vụ GraphQL được quản lý cho phép thiết kế API linh hoạt và đồng bộ hóa dữ liệu theo thời gian thực.
- **CodePipeline**: Dịch vụ tích hợp và triển khai liên tục (CI/CD) tự động hóa quy trình phát hành ứng dụng.
