---
title: "Nhật ký công việc Tuần 4"
date: 11-05-2026
weight: 4
chapter: false
pre: " <b> 1.4. </b> "
---

### Mục tiêu Tuần 4:

* Tìm hiểu dịch vụ cơ sở dữ liệu quan hệ được quản lý Amazon RDS (Relational Database Service).
* Làm quen với Amazon Lightsail – giải pháp điện toán đơn giản trên AWS.
* Tìm hiểu các chiến lược tối ưu chi phí khi sử dụng AWS.
* Nắm vững các tính năng giám sát và ghi nhật ký với Amazon CloudWatch.

### Các công việc thực hiện trong tuần:

| Chủ đề | Công việc | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| --- | --- | --- | --- | --- |
| Dịch vụ cơ sở dữ liệu | **Amazon Relational Database Service (Amazon RDS)** <br> - Tạo và cấu hình Amazon RDS Instance <br> - Thiết lập Multi-AZ để tăng tính sẵn sàng <br> - Cấu hình sao lưu tự động và Snapshot <br> - Tìm hiểu Read Replica để mở rộng khả năng đọc | 11/05/2026 | 11/05/2026 | <https://000005.awsstudygroup.com/> |
| Điện toán & Tối ưu chi phí | **Workshop Amazon Lightsail - Cost Optimization on AWS** <br> - Khởi tạo Lightsail Instance <br> - Tìm hiểu mô hình chi phí của Lightsail <br> - So sánh Lightsail với Amazon EC2 <br> - Tìm hiểu các phương pháp tối ưu chi phí | 13/05/2026 | 13/05/2026 | <https://000045.awsstudygroup.com/> |
| Dịch vụ Container | **Amazon Lightsail Container - Run Apps on Lightsail Container** <br> - Triển khai ứng dụng container trên Lightsail <br> - Tìm hiểu kiến thức cơ bản về Container <br> - Cấu hình Load Balancer <br> - Quản lý và cập nhật Container | 15/05/2026 | 15/05/2026 | <https://000046.awsstudygroup.com/> |
| Giám sát & Quan sát hệ thống | **AWS CloudWatch Workshop** <br> - Tạo và giám sát Metrics <br> - Thiết lập CloudWatch Alarm <br> - Sử dụng CloudWatch Logs để quản lý nhật ký <br> - Tạo Dashboard theo dõi hệ thống | 17/05/2026 | 17/05/2026 | <https://000008.awsstudygroup.com/> |

# Kết quả đạt được trong Tuần 4

## Quản lý cơ sở dữ liệu với Amazon RDS

- Khởi tạo và cấu hình thành công **Amazon RDS Instance** với nhiều hệ quản trị cơ sở dữ liệu như MySQL, PostgreSQL, MariaDB, Oracle và SQL Server.
- Tìm hiểu **Multi-AZ Deployment**, giúp tăng tính sẵn sàng và tự động chuyển đổi khi xảy ra sự cố giữa các Availability Zone.
- Cấu hình **Automated Backup**, Point-in-Time Recovery và Snapshot để đảm bảo an toàn dữ liệu.
- Tìm hiểu **Read Replica** nhằm phân tán tải truy vấn đọc và cải thiện hiệu năng của hệ thống.

## Điện toán đơn giản với Amazon Lightsail

- Triển khai **Amazon Lightsail Instance** như một giải pháp đơn giản hơn so với Amazon EC2.
- So sánh **Amazon Lightsail** và **Amazon EC2** để hiểu ưu điểm, hạn chế và các trường hợp sử dụng phù hợp của từng dịch vụ.
- Tìm hiểu các phương pháp tối ưu chi phí như lựa chọn cấu hình phù hợp, theo dõi tài nguyên không sử dụng và quản lý chi phí hiệu quả.

## Triển khai Container trên Amazon Lightsail

- Triển khai thành công **ứng dụng Container** trên Amazon Lightsail Container.
- Cấu hình **Load Balancer** để phân phối lưu lượng truy cập giữa các Container.
- Hiểu quy trình triển khai Image, cập nhật Container và khả năng mở rộng ứng dụng trên nền tảng Lightsail.

## Giám sát hệ thống với Amazon CloudWatch

- Tạo và theo dõi **CloudWatch Metrics** để giám sát các chỉ số như CPU, bộ nhớ, dung lượng lưu trữ và lưu lượng mạng.
- Thiết lập **CloudWatch Alarm** để gửi cảnh báo khi các chỉ số vượt quá ngưỡng cho phép.
- Thu thập và quản lý **CloudWatch Logs** nhằm hỗ trợ theo dõi, phân tích và xử lý lỗi của hệ thống.
- Xây dựng **CloudWatch Dashboard** để trực quan hóa các chỉ số hoạt động của hạ tầng AWS.

### Tóm tắt lý thuyết

- **Amazon RDS:** Dịch vụ cơ sở dữ liệu quan hệ được AWS quản lý, hỗ trợ tự động sao lưu, cập nhật và tăng tính sẵn sàng của hệ thống.
- **Multi-AZ:** Cơ chế triển khai nhiều Availability Zone giúp tự động chuyển đổi khi xảy ra sự cố và nâng cao độ tin cậy.
- **Amazon Lightsail:** Dịch vụ điện toán đơn giản, phù hợp với các dự án nhỏ, website và người mới bắt đầu làm quen với AWS.
- **Amazon CloudWatch:** Dịch vụ giám sát của AWS dùng để theo dõi Metrics, Logs, Alarm và Dashboard, hỗ trợ quản lý và vận hành hệ thống hiệu quả.
- **Metrics & Alarms:** Các chỉ số và cảnh báo giúp giám sát tài nguyên theo thời gian thực và phản ứng kịp thời khi xảy ra sự cố.