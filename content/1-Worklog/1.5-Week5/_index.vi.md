---
title: "Nhật ký công việc Tuần 5"
date: 18-05-2026
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---

### Mục tiêu Tuần 5:

* Thành thạo dịch vụ DNS với Amazon Route 53 và cấu hình Hybrid DNS.
* Nâng cao kỹ năng sử dụng AWS CLI để tự động hóa quản lý hạ tầng.
* Tìm hiểu Amazon ElastiCache nhằm cải thiện hiệu năng ứng dụng bằng bộ nhớ đệm.
* Hiểu các chiến lược và công cụ hỗ trợ di chuyển cơ sở dữ liệu.
* Tìm hiểu các giải pháp khôi phục sau thảm họa (Disaster Recovery) trên AWS.

### Các công việc thực hiện trong tuần:

| Chủ đề | Công việc | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| --- | --- | --- | --- | --- |
| DNS & Kết nối Hybrid | **Thiết lập Hybrid DNS với Route 53 Resolver** <br> - Cấu hình Route 53 Hosted Zone <br> - Thiết lập Route 53 Resolver cho Hybrid DNS <br> - Tạo chính sách DNS Failover <br> - Tìm hiểu các chính sách định tuyến DNS | 18/05/2026 | 18/05/2026 | <https://000010.awsstudygroup.com/> |
| Tự động hóa hạ tầng | **Làm quen với AWS CLI** <br> - Thành thạo cú pháp AWS CLI <br> - Tự động hóa các thao tác với EC2, S3 và RDS <br> - Cấu hình Profile và Credentials <br> - Viết Script quản lý hạ tầng | 19/05/2026 | 19/05/2026 | <https://000011.awsstudygroup.com/> |
| Bộ nhớ đệm & Hiệu năng | **Amazon ElastiCache - Redis** <br> - Triển khai Redis Cluster <br> - Tìm hiểu các mô hình và chiến lược Cache <br> - Cấu hình Replication và Failover <br> - Giám sát hiệu năng Cache | 21/05/2026 | 21/05/2026 | <https://000061.awsstudygroup.com/> |
| Di chuyển dữ liệu | **Chuyển đổi và Di chuyển Cơ sở dữ liệu** <br> - Đánh giá khả năng di chuyển <br> - Chuyển đổi Schema giữa các hệ quản trị CSDL <br> - Di chuyển dữ liệu với thời gian gián đoạn tối thiểu <br> - Kiểm tra tính toàn vẹn của dữ liệu sau khi di chuyển | 23/05/2026 | 23/05/2026 | <https://000043.awsstudygroup.com/> |
| Khôi phục sau thảm họa | **Workshop AWS Elastic Disaster Recovery** <br> - Tìm hiểu khái niệm RTO và RPO <br> - Thiết lập Replication và Failover <br> - Xây dựng kế hoạch khôi phục sau thảm họa <br> - Kiểm thử quy trình khôi phục | 24/05/2026 | 24/05/2026 | <https://000100.awsstudygroup.com/> |

# Kết quả đạt được trong Tuần 5

## Quản lý DNS với Amazon Route 53

- Cấu hình thành công **Route 53 Hosted Zone** và các bản ghi DNS để quản lý tên miền.
- Thiết lập **Route 53 Resolver** nhằm hỗ trợ phân giải DNS giữa hệ thống On-premises và AWS VPC trong môi trường Hybrid Cloud.
- Tìm hiểu **DNS Failover Policy**, cho phép tự động chuyển hướng lưu lượng truy cập đến các tài nguyên còn hoạt động khi tài nguyên chính gặp sự cố.
- Hiểu các **chính sách định tuyến DNS** như Simple, Weighted, Latency-based, Failover và Geolocation để tối ưu việc phân phối lưu lượng truy cập.

## Thành thạo AWS CLI

- Nắm vững **cấu trúc lệnh AWS CLI**, giúp quản lý hạ tầng AWS thông qua giao diện dòng lệnh.
- Tự động hóa các thao tác trên **EC2, Amazon S3, Amazon RDS** và nhiều dịch vụ AWS khác bằng AWS CLI.
- Cấu hình **nhiều Profile và Credentials**, hỗ trợ quản lý nhiều tài khoản AWS trên cùng một máy.
- Xây dựng các **Script tự động hóa** cho những tác vụ lặp lại như quản lý EC2 Instance, sao lưu dữ liệu và cập nhật Security Group.

## Bộ nhớ đệm với Amazon ElastiCache

- Triển khai **Redis Cluster** trên Amazon ElastiCache nhằm tăng tốc độ truy xuất dữ liệu.
- Tìm hiểu các **mô hình Cache** như Cache Aside, Write-through và Write-behind cùng các trường hợp sử dụng phù hợp.
- Cấu hình **Replication** và **Failover** nhằm tăng tính sẵn sàng cho hệ thống Cache.
- Theo dõi **Cache Hit Ratio** và các chính sách loại bỏ dữ liệu (Eviction Policy) để tối ưu hiệu năng và chi phí.

## Chiến lược di chuyển cơ sở dữ liệu

- Đánh giá khả năng di chuyển cơ sở dữ liệu bằng **AWS Database Migration Service (DMS)**.
- Chuyển đổi **Schema** giữa các hệ quản trị cơ sở dữ liệu khác nhau (ví dụ Oracle sang PostgreSQL).
- Thực hiện **di chuyển dữ liệu** với thời gian gián đoạn tối thiểu thông qua cơ chế sao chép liên tục.
- Kiểm tra **tính toàn vẹn của dữ liệu** sau quá trình di chuyển bằng các phương pháp đối chiếu và xác thực.

## Khôi phục sau thảm họa

- Hiểu các chỉ số quan trọng trong Disaster Recovery gồm **RTO (Recovery Time Objective)** và **RPO (Recovery Point Objective)**.
- Cấu hình **AWS Elastic Disaster Recovery** để sao chép liên tục dữ liệu từ hệ thống On-premises hoặc môi trường ngoài AWS lên AWS.
- Xây dựng **kế hoạch khôi phục sau thảm họa**, bao gồm quy trình chuyển đổi và khôi phục hệ thống.
- Thực hiện kiểm thử quy trình khôi phục nhằm đảm bảo tính sẵn sàng của hệ thống.

### Tóm tắt lý thuyết

- **Amazon Route 53:** Dịch vụ DNS được quản lý của AWS, hỗ trợ đăng ký tên miền, phân giải DNS và định tuyến lưu lượng dựa trên trạng thái sức khỏe của tài nguyên.
- **AWS CLI:** Công cụ dòng lệnh cho phép truy cập và quản lý các dịch vụ AWS theo cách tự động hóa, hỗ trợ triển khai hạ tầng theo hướng Infrastructure as Code.
- **Amazon ElastiCache:** Dịch vụ bộ nhớ đệm trong bộ nhớ (Redis hoặc Memcached) giúp giảm tải cho cơ sở dữ liệu và cải thiện hiệu năng ứng dụng.
- **Database Migration:** Quá trình di chuyển dữ liệu từ hệ thống cũ sang AWS, bao gồm chuyển đổi Schema, giảm thời gian gián đoạn và đảm bảo tính toàn vẹn dữ liệu.
- **Disaster Recovery:** Các chiến lược và công cụ giúp khôi phục hệ thống khi xảy ra sự cố, trong đó RTO và RPO là hai chỉ số quan trọng để đánh giá mục tiêu khôi phục.