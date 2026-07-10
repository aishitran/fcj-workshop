---
title: "Nhật ký công việc Tuần 6"
date: 2026-05-25
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---

### Mục tiêu Tuần 6:

* Tìm hiểu cơ sở dữ liệu NoSQL với Amazon DynamoDB.
* Làm quen với mô hình điện toán Serverless thông qua AWS Lambda và các phương pháp tối ưu chi phí.
* Nắm vững dịch vụ phân phối nội dung Amazon CloudFront.
* Tối ưu hiệu năng ứng dụng và giảm độ trễ khi truy cập trên phạm vi toàn cầu.

### Các công việc thực hiện trong tuần:

| Chủ đề | Công việc | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| --- | --- | --- | --- | --- |
| Cơ sở dữ liệu NoSQL | **Làm việc với Amazon DynamoDB** <br> - Tạo và quản lý bảng DynamoDB <br> - Tìm hiểu Partition Key và Sort Key <br> - Cấu hình chế độ đọc/ghi dữ liệu <br> - Tìm hiểu Global Tables để phân phối dữ liệu đa khu vực | 25/05/2026 | 25/05/2026 | <https://000060.awsstudygroup.com/> |
| Serverless & Tối ưu chi phí | **Tối ưu chi phí EC2 bằng AWS Lambda** <br> - Tạo Lambda Function để tự động hóa tác vụ <br> - Sử dụng Lambda thay thế hoặc hỗ trợ EC2 <br> - Tìm hiểu mô hình tính phí theo số lần thực thi <br> - Tối ưu hiệu năng và thời gian thực thi của Lambda | 28/05/2026 | 28/05/2026 | <https://000022.awsstudygroup.com/> |
| Phân phối nội dung | **CloudFront với S3 Bucket Origin** <br> - Tạo CloudFront Distribution <br> - Cấu hình S3 làm Origin <br> - Thiết lập Cache Behavior và TTL <br> - Thực hiện Cache Invalidation khi cập nhật nội dung | 30/05/2026 | 30/05/2026 | <https://000094.awsstudygroup.com/> |

# Kết quả đạt được trong Tuần 6

## Cơ sở dữ liệu NoSQL với Amazon DynamoDB

- Tạo và quản lý thành công **Amazon DynamoDB Table** với mô hình dữ liệu linh hoạt.
- Hiểu vai trò của **Partition Key** và **Sort Key** trong việc phân phối dữ liệu và tối ưu hiệu năng truy vấn.
- Cấu hình các chế độ **Provisioned Capacity** và **On-demand Capacity**, đồng thời hiểu ưu nhược điểm của từng chế độ.
- Tìm hiểu **DynamoDB Streams** để ghi nhận thay đổi dữ liệu và tích hợp với các dịch vụ AWS khác.
- Làm quen với **Global Tables**, cho phép sao chép dữ liệu giữa nhiều Region nhằm tăng khả năng sẵn sàng và giảm độ trễ.

## Điện toán Serverless với AWS Lambda

- Xây dựng các **AWS Lambda Function** để tự động hóa nhiều tác vụ mà không cần quản lý máy chủ.
- Hiểu cách **AWS Lambda** tính chi phí dựa trên số lần thực thi và thời gian chạy, giúp tối ưu chi phí cho các khối lượng công việc không liên tục.
- Sử dụng **Lambda** để thay thế hoặc hỗ trợ EC2 trong các tác vụ như xử lý dữ liệu, chạy theo lịch và xây dựng API.
- Tối ưu **hiệu năng Lambda** thông qua việc điều chỉnh bộ nhớ, thời gian thực thi và quản lý thư viện phụ thuộc.
- Tìm hiểu **Lambda Layers** để tái sử dụng mã nguồn và giảm kích thước gói triển khai.

## Phân phối nội dung với Amazon CloudFront

- Tạo **CloudFront Distribution** để phân phối nội dung từ các Edge Location gần người dùng nhất.
- Cấu hình **Amazon S3** làm Origin cho việc phân phối nội dung tĩnh.
- Thiết lập **Cache Behavior** và **Time-to-Live (TTL)** nhằm cân bằng giữa hiệu năng và khả năng cập nhật dữ liệu.
- Thực hiện **Cache Invalidation** để xóa nội dung cũ khỏi bộ nhớ đệm khi có phiên bản mới.
- Hiểu cách **Edge Location** giúp giảm độ trễ và cải thiện tốc độ truy cập trên phạm vi toàn cầu.

### Tóm tắt lý thuyết

- **Amazon DynamoDB:** Dịch vụ cơ sở dữ liệu NoSQL được AWS quản lý hoàn toàn, cung cấp hiệu năng cao với khả năng mở rộng linh hoạt và độ trễ rất thấp.
- **Partition Key:** Khóa chính dùng để phân phối dữ liệu trên các Partition của DynamoDB, ảnh hưởng trực tiếp đến hiệu năng và khả năng mở rộng.
- **AWS Lambda:** Dịch vụ điện toán Serverless cho phép chạy mã nguồn theo sự kiện mà không cần quản lý máy chủ.
- **Amazon CloudFront:** Dịch vụ CDN (Content Delivery Network) của AWS giúp phân phối nội dung từ các Edge Location nhằm giảm độ trễ và tăng tốc độ truy cập.
- **TTL (Time-to-Live):** Thời gian CloudFront lưu trữ dữ liệu trong bộ nhớ đệm trước khi lấy phiên bản mới từ Origin.