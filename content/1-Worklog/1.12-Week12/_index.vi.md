=---
title: "Nhật ký công việc Tuần 12"
date: 2026-07-06
weight: 12
chapter: false
pre: " <b> 1.12. </b> "
---

### Mục tiêu Tuần 12:

* Hỗ trợ team hoàn thiện phần hạ tầng còn thiếu cho dự án ReviewSentinel.
* Hỗ trợ triển khai và kiểm tra các hàm Lambda cùng trigger tương ứng.
* Tham gia rà soát, phát hiện các lỗi cấu hình phát sinh trong pipeline.
* Theo dõi việc dựng API Gateway và chuyển đổi sang luồng xác thực thật.
* Tham gia kiểm thử hệ thống bằng dữ liệu mẫu và hỗ trợ chuẩn bị tài liệu dự án.

### Các công việc thực hiện trong tuần:

| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| --- | --- | --- | --- | --- |
| 2 | **Hoàn thiện hạ tầng còn thiếu** <br> - Hỗ trợ team dựng nốt các thành phần hạ tầng còn lại của ReviewSentinel | 07/07/2026 | 07/07/2026 | AWS Study Group |
| 3 | **Triển khai Lambda function** <br> - Hỗ trợ triển khai và kiểm tra 3 Lambda function chính <br> - Kiểm tra trigger tương ứng (S3, DynamoDB Stream, EventBridge) | 08/07/2026 | 08/07/2026 | AWS Study Group |
| 4 | **Rà soát lỗi cấu hình** <br> - Tham gia rà soát pipeline, phát hiện một số lỗi cấu hình phát sinh | 09/07/2026 | 09/07/2026 | AWS Study Group |
| 5 | **API Gateway & xác thực** <br> - Theo dõi việc dựng API Gateway với Cognito authorizer <br> - Quan sát/hỗ trợ chuyển đổi sang luồng đăng nhập thật qua Cognito Hosted UI | 10/07/2026 | 10/07/2026 | AWS Study Group |
| 6 | **Kiểm thử & tài liệu** <br> - Tham gia kiểm thử hệ thống bằng dữ liệu mẫu <br> - Hỗ trợ chuẩn bị tài liệu dự án | 11/07/2026 | 11/07/2026 | AWS Study Group |

# Kết quả đạt được trong Tuần 12

## Hoàn thiện hạ tầng

- Hỗ trợ team dựng nốt các thành phần hạ tầng còn thiếu cho ReviewSentinel.

## Triển khai Lambda

- Hỗ trợ triển khai và kiểm tra 3 Lambda function chính cùng các trigger tương ứng (S3, DynamoDB Stream, EventBridge).

## Rà soát lỗi cấu hình

- Tham gia rà soát pipeline và phát hiện một số lỗi cấu hình phát sinh trong quá trình chạy thử.

## API Gateway & Xác thực

- Theo dõi quá trình dựng API Gateway với Cognito authorizer.
- Quan sát và hỗ trợ quá trình chuyển đổi sang luồng đăng nhập thật qua Cognito Hosted UI.

## Kiểm thử & Tài liệu

- Tham gia kiểm thử hệ thống bằng dữ liệu mẫu.
- Hỗ trợ chuẩn bị tài liệu dự án.

### Tóm tắt lý thuyết

- **AWS Lambda Trigger** cho phép hàm Lambda tự động được gọi khi có sự kiện từ S3, DynamoDB Stream hoặc EventBridge.
- **Amazon API Gateway** kết hợp với **Cognito Authorizer** giúp xác thực request trước khi vào đến backend.
- **Cognito Hosted UI** cung cấp giao diện đăng nhập/đăng ký có sẵn, tích hợp trực tiếp với luồng OAuth 2.0.
- Việc rà soát lỗi cấu hình (filter sai điều kiện, thiếu quyền IAM, alarm thiếu dimension...) là bước quan trọng để đảm bảo pipeline hoạt động đúng như thiết kế.
