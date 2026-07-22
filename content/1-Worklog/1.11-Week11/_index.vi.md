---
title: "Nhật ký Tuần 11"
date: 2026-06-29
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---

### Mục tiêu Tuần 11:

* Chốt kiến trúc tổng thể cho dự án ReviewSentinel.
* Xác định mô hình bảo mật cho hệ thống (xác thực, phân quyền).
* Thiết kế lược đồ dữ liệu DynamoDB cho ứng dụng.
* Soạn đặc tả các Lambda function chính sẽ triển khai.
* Tìm hiểu thêm một số dịch vụ AWS phục vụ vận hành và bảo mật.

### Các công việc thực hiện trong tuần:

| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| --- | --- | --- | --- | --- |
| 2 | **Chốt kiến trúc tổng thể** <br> - Cùng team thống nhất kiến trúc ReviewSentinel: lớp edge, ứng dụng, xử lý, phân tích AI, giám sát | 30/06/2026 | 30/06/2026 | AWS Study Group |
| 3 | **Xác định mô hình bảo mật** <br> - Xác định luồng xác thực Cognito <br> - Xác định phân quyền IAM theo nguyên tắc tối thiểu <br> - Xác định phân quyền ở tầng API Gateway | 01/07/2026 | 01/07/2026 | AWS Study Group |
| 4 | **Thiết kế lược đồ DynamoDB** <br> - Thiết kế bảng Reviews, Products, Users <br> - Xác định các mẫu truy vấn sẽ sử dụng | 02/07/2026 | 02/07/2026 | AWS Study Group |
| 5 | **Soạn đặc tả Lambda function** <br> - Mô tả chi tiết các function: review-processor, sentiment-analyzer, API handler <br> - Xác định trigger tương ứng cho từng function | 03/07/2026 | 03/07/2026 | AWS Study Group |
| 6 | **Tìm hiểu thêm dịch vụ hỗ trợ** <br> - Tìm hiểu EBS Data Lifecycle Manager <br> - Tìm hiểu AWS SSO <br> - Tìm hiểu IAM Permission Boundaries <br> - Tìm hiểu AWS Security Hub | 04/07/2026 | 04/07/2026 | AWS Study Group |

# Kết quả đạt được trong Tuần 11

## Kiến trúc tổng thể

- Cùng team chốt kiến trúc tổng thể của ReviewSentinel, gồm 5 lớp: edge, ứng dụng, xử lý, phân tích AI và giám sát.

## Mô hình bảo mật

- Xác định luồng xác thực người dùng qua Amazon Cognito.
- Xác định cách phân quyền IAM theo nguyên tắc tối thiểu (least privilege).
- Xác định cách phân quyền ở tầng API Gateway.

## Lược đồ dữ liệu DynamoDB

- Thiết kế các bảng chính: Reviews, Products, Users.
- Xác định các mẫu truy vấn (query pattern) sẽ dùng cho từng bảng.

## Đặc tả Lambda function

- Soạn đặc tả cho 3 Lambda function chính: review-processor, sentiment-analyzer, API handler.
- Xác định trigger tương ứng cho từng function.

## Tìm hiểu thêm

- Tìm hiểu EBS Data Lifecycle Manager, AWS SSO, IAM Permission Boundaries và AWS Security Hub.

### Tóm tắt lý thuyết

- **Amazon Cognito** cung cấp cơ chế xác thực và quản lý người dùng an toàn thông qua User Pool và JWT token.
- **IAM Least Privilege** là nguyên tắc chỉ cấp đúng quyền cần thiết cho từng vai trò, hạn chế rủi ro bảo mật.
- **Amazon DynamoDB** là cơ sở dữ liệu NoSQL được quản lý hoàn toàn, thiết kế lược đồ tốt giúp tối ưu hiệu năng truy vấn.
- **AWS Lambda** thực thi mã theo sự kiện, phù hợp với kiến trúc serverless khi được kích hoạt qua các trigger như S3, DynamoDB Stream, EventBridge.
- **AWS Security Hub** tổng hợp và đánh giá tình trạng bảo mật trên toàn tài khoản AWS theo các chuẩn như CIS, PCI DSS.
