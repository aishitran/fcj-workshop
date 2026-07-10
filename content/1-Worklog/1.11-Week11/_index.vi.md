---
title: "Nhật ký công việc Tuần 11"
date: 29-06-2026
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---

### Mục tiêu Tuần 11:

* Chuẩn bị các tài nguyên AWS cần thiết cho dự án ReviewSentinel dựa trên kiến trúc đã được thống nhất.
* Cấu hình các thành phần xác thực và phân quyền bằng Amazon Cognito và IAM.
* Chuẩn bị các bảng DynamoDB và bucket Amazon S3 phục vụ lưu trữ dữ liệu của ứng dụng.
* Chuẩn bị nền tảng cho việc tích hợp các hàm AWS Lambda.
* Tổ chức cấu trúc dự án Terraform để triển khai hạ tầng.
* Kiểm tra cấu hình hạ tầng trước khi bước sang giai đoạn triển khai ở Tuần 12.

### Các công việc thực hiện trong tuần:

| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| --- | --- | --- | --- | --- |
| 2 | **Chuẩn bị hạ tầng AWS** <br> - Rà soát kiến trúc ReviewSentinel đã được thống nhất <br> - Kiểm tra mối liên kết giữa API Gateway, Lambda, DynamoDB và Amazon S3 <br> - Chuẩn bị các tài nguyên AWS phục vụ cho việc triển khai | 29/06/2026 | 29/06/2026 | AWS Study Group |
| 3 | **Cấu hình xác thực và phân quyền** <br> - Cấu hình Amazon Cognito User Pool <br> - Chuẩn bị IAM Roles và IAM Policies theo nguyên tắc Least Privilege <br> - Kiểm tra luồng xác thực JWT | 30/06/2026 | 30/06/2026 | AWS Study Group |
| 4 | **Chuẩn bị tài nguyên lưu trữ dữ liệu** <br> - Tạo cấu trúc các bảng DynamoDB <br> - Chuẩn bị Amazon S3 Bucket để lưu trữ dữ liệu đánh giá <br> - Kiểm tra cấu hình Event Notification | 01/07/2026 | 01/07/2026 | AWS Study Group |
| 5 | **Chuẩn bị triển khai Lambda** <br> - Hoàn thiện cấu trúc các hàm Lambda <br> - Cấu hình Environment Variables <br> - Chuẩn bị CloudWatch Logging và cơ chế xử lý lỗi | 02/07/2026 | 02/07/2026 | AWS Study Group |
| 6 | **Hoàn thiện cấu trúc Terraform** <br> - Cập nhật Providers và Modules <br> - Chuẩn bị các tài nguyên hạ tầng cơ bản <br> - Kiểm tra quy trình triển khai hạ tầng | 03/07/2026 | 03/07/2026 | AWS Study Group |

# Kết quả đạt được trong Tuần 11

## Chuẩn bị hạ tầng AWS

- Đã rà soát kiến trúc ReviewSentinel và kiểm tra mối liên kết giữa API Gateway, AWS Lambda, Amazon DynamoDB, Amazon S3, Amazon Comprehend và Amazon Bedrock.
- Chuẩn bị các tài nguyên AWS cần thiết để phục vụ quá trình triển khai hệ thống.
- Xác nhận việc bố trí các thành phần hạ tầng phù hợp với luồng hoạt động của ứng dụng.

## Cấu hình xác thực và phân quyền

- Hoàn thành cấu hình **Amazon Cognito User Pool** phục vụ xác thực người dùng.
- Chuẩn bị **IAM Roles** và **IAM Policies** theo nguyên tắc **Least Privilege** cho các hàm Lambda.
- Kiểm tra luồng xác thực bằng **JWT Token** giữa Amazon Cognito và API Gateway.

## Chuẩn bị tài nguyên lưu trữ

- Chuẩn bị các bảng **Amazon DynamoDB** phục vụ lưu trữ dữ liệu **Reviews**, **Products** và **Users**.
- Cấu hình **Amazon S3 Bucket** để lưu trữ dữ liệu đánh giá được tải lên.
- Kiểm tra cấu hình **Event Notification** giữa Amazon S3 và AWS Lambda nhằm phục vụ xử lý tự động.

## Chuẩn bị triển khai Lambda

- Hoàn thiện cấu trúc các hàm AWS Lambda theo chức năng được phân công.
- Chuẩn bị các biến môi trường (Environment Variables) và các thiết lập thực thi.
- Cấu hình **Amazon CloudWatch Logs** để hỗ trợ giám sát và xử lý lỗi trong quá trình phát triển.

## Chuẩn bị hạ tầng với Terraform

- Hoàn thiện cấu trúc dự án Terraform gồm **Providers**, **Variables** và **Modules**.
- Chuẩn bị các tệp cấu hình **Infrastructure as Code (IaC)** để triển khai tài nguyên AWS.
- Kiểm tra quy trình triển khai nhằm đảm bảo hạ tầng sẵn sàng cho giai đoạn phát triển tiếp theo.

### Tóm tắt lý thuyết

- **Amazon Cognito** là dịch vụ quản lý người dùng và xác thực, sử dụng **User Pool** và **JWT Token** để bảo vệ ứng dụng.
- **AWS Lambda** là dịch vụ điện toán không máy chủ (Serverless), cho phép thực thi mã nguồn khi có sự kiện từ các dịch vụ AWS.
- **Amazon DynamoDB** là cơ sở dữ liệu NoSQL được quản lý hoàn toàn, có khả năng mở rộng cao và hiệu năng ổn định.
- **Amazon S3** là dịch vụ lưu trữ đối tượng có độ bền cao và có thể kích hoạt các quy trình xử lý thông qua **Event Notification**.
- **Terraform** là công cụ **Infrastructure as Code (IaC)** giúp tự động hóa việc triển khai và quản lý hạ tầng AWS bằng các tệp cấu hình có thể tái sử dụng.