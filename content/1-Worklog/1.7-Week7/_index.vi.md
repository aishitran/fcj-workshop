---
title: "Nhật ký công việc Tuần 7"
date: 01-06-2026
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---

### Mục tiêu Tuần 7:

* Đào sâu kiến thức về ElastiCache và các mẫu caching nâng cao.
* Học cách di chuyển máy ảo (VM) từ hạ tầng on-premises lên AWS.
* Tiếp tục di chuyển và tối ưu hóa cơ sở dữ liệu.
* Thành thạo giám sát hệ thống với công cụ mã nguồn mở Grafana.
* Tiếp tục khám phá Lambda để tối ưu chi phí.

### Các nhiệm vụ thực hiện trong tuần:

| Chủ đề | Nhiệm vụ | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| --- | --- | --- | --- | --- |
| Caching & Hiệu năng | **Amazon ElastiCache – Redis** <br> - Triển khai cấu hình Redis nâng cao <br> - Hiểu về chế độ cluster và tính sẵn sàng cao <br> - Triển khai các mẫu caching phức tạp <br> - Tinh chỉnh tham số hiệu năng Redis | 01/06/2026 | 01/06/2026 | <https://000061.awsstudygroup.com/> |
| Di chuyển & Lift-and-Shift | **VM Import/Export** <br> - Xuất VM từ hạ tầng on-premises sang AWS <br> - Nhập VM dưới dạng EC2 instance <br> - Hiểu các định dạng và công cụ được hỗ trợ <br> - Lập kế hoạch chiến lược di chuyển lift-and-shift | 02/06/2026 | 02/06/2026 | <https://000014.awsstudygroup.com/> |
| Di chuyển dữ liệu | **Chuyển đổi & Di chuyển Schema Cơ sở dữ liệu** <br> - Xử lý các phép biến đổi schema phức tạp <br> - Quản lý chuyển đổi kiểu dữ liệu <br> - Triển khai chiến lược kiểm tra tính hợp lệ khi di chuyển <br> - Lập kế hoạch quy trình chuyển đổi (cutover) | 03/06/2026 | 03/06/2026 | <https://000043.awsstudygroup.com/> |
| Giám sát & Trực quan hóa | **Bắt đầu với Grafana cơ bản** <br> - Triển khai và cấu hình Grafana <br> - Tạo dashboard giám sát hạ tầng <br> - Kết nối nguồn dữ liệu (CloudWatch, Prometheus) <br> - Thiết lập cảnh báo và thông báo | 04/06/2026 | 04/06/2026 | <https://000029.awsstudygroup.com/> |
| Tối ưu hóa Serverless | **Tối ưu chi phí EC2 với Lambda** <br> - Xây dựng các giải pháp Lambda nâng cao <br> - Sử dụng Lambda cho tác vụ định kỳ và xử lý theo lô <br> - Tối ưu cold start của Lambda <br> - Triển khai Lambda@Edge để xử lý nội dung | 05/06/2026 | 05/06/2026 | <https://000022.awsstudygroup.com/> |

# Thành tựu Tuần 7

## ElastiCache & Caching Nâng cao
- Triển khai **cấu hình Redis nâng cao** bao gồm chế độ cluster để phân mảnh dữ liệu (sharding) và tự động chuyển đổi dự phòng (failover).
- Hiểu về **replication đa vùng khả dụng (multi-AZ)** trong ElastiCache để đạt tính sẵn sàng cao mà không cần can thiệp thủ công.
- Triển khai các **mẫu caching phức tạp** như cache-aside, write-through, và Bloom filter cho các mẫu truy cập dữ liệu tinh vi.
- Tinh chỉnh **các tham số Redis** (chính sách maxmemory, thuật toán eviction, cài đặt timeout) để đạt hiệu năng tối ưu.

## Di chuyển VM lên AWS
- Học quy trình **VM Import/Export** để di chuyển máy ảo từ hypervisor on-premises sang EC2 trên AWS.
- Hiểu các định dạng được hỗ trợ và yêu cầu chuyển đổi cho các nền tảng nguồn khác nhau (VMware, Hyper-V, KVM, v.v.).
- Thực hiện chiến lược **di chuyển lift-and-shift**, chuyển hạ tầng hiện có sang AWS với thay đổi tối thiểu.
- Kiểm tra **tính tương thích của VM** và thực hiện các điều chỉnh cấu hình sau di chuyển.

## Di chuyển Cơ sở dữ liệu Nâng cao
- Xử lý các **phép biến đổi schema phức tạp** giữa các hệ quản trị cơ sở dữ liệu có cấu trúc khác nhau.
- Quản lý **chuyển đổi kiểu dữ liệu** và đảm bảo tính tương thích trong quá trình di chuyển liên nền tảng.
- Triển khai **chiến lược kiểm tra toàn diện** để phát hiện và xử lý các vấn đề về tính nhất quán dữ liệu.
- Lập kế hoạch và thực hiện **quy trình cutover** với thời gian downtime ứng dụng tối thiểu.

## Ngăn xếp Giám sát Grafana
- Triển khai và cấu hình **Grafana** như một nền tảng trực quan hóa và phân tích mã nguồn mở.
- Tạo **dashboard tùy chỉnh** hiển thị số liệu hạ tầng theo thời gian thực từ nhiều nguồn.
- Kết nối **các nguồn dữ liệu** bao gồm CloudWatch, Prometheus và các hệ thống giám sát khác.
- Thiết lập **cảnh báo và thông báo** cho các sự cố vận hành và vi phạm ngưỡng.

## Tối ưu Lambda Nâng cao
- Xây dựng **các giải pháp Lambda nâng cao** cho các trường hợp sử dụng phức tạp hơn xử lý sự kiện đơn giản.
- Sử dụng **Lambda để xử lý theo lô định kỳ** thông qua EventBridge, thay thế cron job truyền thống và máy chủ xử lý batch.
- Tối ưu **cold start của Lambda** thông qua tái cấu trúc mã, giảm phụ thuộc và tinh chỉnh bộ nhớ.
- Khám phá **Lambda@Edge** để thực thi hàm tại các điểm biên (edge location) của CloudFront nhằm cá nhân hóa nội dung và bảo mật.

### Tóm tắt lý thuyết
- **Redis Cluster Mode**: Phân mảnh dữ liệu trên nhiều node Redis, cho phép mở rộng theo chiều ngang và hỗ trợ tập dữ liệu lớn hơn dung lượng một node đơn.
- **VM Import/Export**: Cơ chế di chuyển máy ảo hiện có lên AWS mà không cần viết lại hoặc cấu hình lại ứng dụng.
- **Grafana**: Nền tảng quan sát (observability) mã nguồn mở cung cấp khả năng trực quan hóa và cảnh báo phong phú trên nhiều nguồn dữ liệu.
- **Cache Patterns**: Các chiến lược khác nhau (cache-aside, write-through, write-behind) để tích hợp caching vào kiến trúc ứng dụng.
- **Lambda Cold Starts**: Độ trễ ban đầu khi Lambda khởi tạo một container mới; có thể được tối ưu thông qua cấu hình và tối ưu mã phù hợp.
