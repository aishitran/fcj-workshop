---
title: "Nhật ký công việc Tuần 3"
date: 04-05-2026
weight: 3
chapter: false
pre: " <b> 1.3. </b> "
---

### Mục tiêu Tuần 3:

* Tìm hiểu AWS Identity and Access Management (IAM) và các nguyên tắc bảo mật trên AWS.
* Hiểu cách cấp quyền cho ứng dụng truy cập các dịch vụ AWS thông qua IAM Role.
* Làm quen với Amazon S3 (Simple Storage Service) để lưu trữ dữ liệu.
* Tìm hiểu về S3 Bucket, cơ chế phân quyền và quản lý dữ liệu.

### Các công việc thực hiện trong tuần:

| Chủ đề | Công việc | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| --- | --- | --- | --- | --- |
| Quản lý danh tính và phân quyền | **Cấp quyền cho ứng dụng truy cập các dịch vụ AWS bằng IAM Role** <br> - Tạo IAM Role và IAM Policy <br> - Tìm hiểu nguyên tắc Least Privilege <br> - Gán IAM Role cho EC2 Instance <br> - Cấu hình truy cập giữa các tài khoản AWS | 04/05/2026 | 04/05/2026 | <https://000048.awsstudygroup.com/> |
| Lưu trữ đối tượng | **Làm quen với Amazon S3** <br> - Tạo và cấu hình S3 Bucket <br> - Tải lên và quản lý đối tượng <br> - Cấu hình Bucket Policy và ACL <br> - Bật Versioning và Static Website Hosting | 08/05/2026 | 08/05/2026 | <https://000057.awsstudygroup.com/> |

# Kết quả đạt được trong Tuần 3

## Quản lý danh tính và phân quyền

- Tạo thành công **IAM Role** và gắn **IAM Policy** để cấp quyền cho ứng dụng truy cập các dịch vụ AWS.
- Hiểu rõ nguyên tắc **Least Privilege (Phân quyền tối thiểu)**, chỉ cấp các quyền cần thiết để đảm bảo an toàn cho hệ thống.
- Thực hành gán **IAM Role cho EC2 Instance**, giúp ứng dụng truy cập các dịch vụ AWS như Amazon S3 hoặc Amazon RDS mà không cần lưu trữ Access Key.
- Tìm hiểu **Trust Relationship** và cơ chế cấp quyền truy cập giữa nhiều tài khoản AWS.

## Kiến thức cơ bản về Amazon S3

- Tạo và cấu hình **Amazon S3 Bucket** để lưu trữ dữ liệu trên AWS.
- Tìm hiểu các **S3 Storage Class** và lựa chọn lớp lưu trữ phù hợp nhằm tối ưu chi phí.
- Cấu hình **Bucket Policy** và **Access Control List (ACL)** để kiểm soát quyền truy cập vào Bucket và các đối tượng.
- Bật **Versioning** nhằm lưu trữ nhiều phiên bản của cùng một đối tượng để bảo vệ dữ liệu.
- Thực hành **Static Website Hosting** để triển khai website tĩnh trực tiếp trên Amazon S3.

### Tóm tắt lý thuyết

- **IAM (Identity and Access Management):** Dịch vụ quản lý danh tính và phân quyền, cho phép kiểm soát người dùng và quyền truy cập đến các tài nguyên AWS thông qua User, Group, Role và Policy.
- **IAM Role:** Cơ chế cấp quyền tạm thời cho người dùng hoặc dịch vụ AWS mà không cần sử dụng Access Key lâu dài.
- **Amazon S3 Bucket:** Vùng chứa dùng để lưu trữ dữ liệu dưới dạng Object với khả năng mở rộng cao và nhiều tùy chọn cấu hình.
- **Least Privilege:** Nguyên tắc bảo mật chỉ cấp đúng các quyền cần thiết để thực hiện công việc.
- **S3 Versioning:** Tính năng lưu giữ nhiều phiên bản của cùng một đối tượng nhằm hỗ trợ khôi phục dữ liệu khi cần thiết.