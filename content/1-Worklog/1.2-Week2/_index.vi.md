---
title: "Nhật ký công việc Tuần 2"
date: 2026-04-27
weight: 2
chapter: false
pre: " <b> 1.2. </b> "
---

### Mục tiêu Tuần 2:

* Hiểu các khái niệm về mạng trong AWS và cách thiết lập Virtual Private Cloud (VPC).
* Tìm hiểu về VPN (Virtual Private Network) và kết nối Site-to-Site VPN để xây dựng môi trường Hybrid Cloud.
* Làm quen với Amazon EC2 (Elastic Compute Cloud) và các tài nguyên điện toán trên AWS.
* Tìm hiểu cách khởi tạo, cấu hình và quản lý các EC2 Instance.

### Các công việc thực hiện trong tuần:

| Chủ đề | Công việc | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| --- | --- | --- | --- | --- |
| Mạng & VPC | **Workshop Amazon VPC và AWS Site-to-Site VPN** <br> - Thiết lập Virtual Private Cloud (VPC) <br> - Cấu hình các Subnet (Public và Private) <br> - Tìm hiểu Route Table và Network ACL <br> - Thực hành kết nối Site-to-Site VPN cho môi trường Hybrid | 27/04/2026 | 27/04/2026 | <https://000003.awsstudygroup.com/> |
| Điện toán | **Giới thiệu về Amazon EC2** <br> - Khởi tạo EC2 Instance <br> - Tìm hiểu các loại và họ EC2 Instance <br> - Cấu hình Security Group và Key Pair <br> - Theo dõi EC2 Instance và quản lý lưu trữ | 30/04/2026 | 30/04/2026 | <https://000004.awsstudygroup.com/> |

# Kết quả đạt được trong Tuần 2

## VPC và Hệ thống mạng

- Thiết lập thành công **Virtual Private Cloud (VPC)** với cấu hình Subnet và định tuyến phù hợp.
- Hiểu cách cấu hình **Public Subnet** và **Private Subnet** để kiểm soát luồng lưu lượng mạng và tăng cường bảo mật.
- Tìm hiểu về **Security Group** (tường lửa trạng thái) và **Network ACL** (tường lửa phi trạng thái) trong việc bảo vệ tài nguyên AWS.
- Thực hành mô hình **Site-to-Site VPN**, cho phép kết nối an toàn giữa hạ tầng tại chỗ (On-premises) và AWS, phục vụ triển khai Hybrid Cloud.

## Kiến thức cơ bản về Amazon EC2

- Khởi tạo và cấu hình thành công **Amazon EC2 Instance**, dịch vụ điện toán cốt lõi của AWS.
- Hiểu các **loại EC2 Instance** (t2, t3, m5, c5...) và cách lựa chọn loại phù hợp theo từng nhu cầu như xử lý tính toán, bộ nhớ hay mục đích sử dụng chung.
- Tìm hiểu về **Key Pair** dùng để kết nối SSH và **Security Group** để kiểm soát lưu lượng truy cập vào và ra khỏi EC2.
- Thực hành các thao tác quản lý vòng đời của EC2 như tạo mới, dừng, khởi động và xóa Instance, đồng thời theo dõi trạng thái thông qua AWS Management Console.

### Tóm tắt lý thuyết

- **VPC (Virtual Private Cloud):** Môi trường mạng riêng biệt trên AWS, cho phép triển khai tài nguyên với khả năng kiểm soát địa chỉ IP, Subnet và định tuyến.
- **Site-to-Site VPN:** Kết nối được mã hóa giữa mạng nội bộ (On-premises) và VPC trên AWS, hỗ trợ xây dựng mô hình Hybrid Cloud.
- **Amazon EC2:** Dịch vụ cung cấp máy chủ ảo có khả năng mở rộng linh hoạt với nhiều cấu hình khác nhau để đáp ứng nhiều loại khối lượng công việc.
- **Security Group:** Tường lửa ảo hoạt động ở cấp độ Instance, giúp kiểm soát lưu lượng truy cập vào và ra khỏi tài nguyên AWS.