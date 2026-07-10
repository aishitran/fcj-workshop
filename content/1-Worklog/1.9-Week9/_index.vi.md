---
title: "Nhật ký công việc Tuần 9"
date: 15/06/2026
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---

### Mục tiêu Tuần 9:

* Hiểu về khái niệm Infrastructure as Code (IaC) và nền tảng AWS CDK.
* Học cách khởi tạo hạ tầng AWS bằng AWS Cloud Development Kit (CDK).
* Hiểu cách lựa chọn loại instance EC2 phù hợp cho từng loại tải công việc.
* Giám sát hạ tầng mạng AWS bằng CloudWatch.
* Quản lý quyền truy cập thanh toán một cách an toàn với IAM.
* Học về hạn ngạch dịch vụ AWS (service quotas) và cách yêu cầu tăng hạn ngạch.
* Khám phá giám sát sử dụng tài nguyên và quản lý chi phí bằng IAM và các dịch vụ thanh toán AWS.

### Các nhiệm vụ thực hiện trong tuần:

| Chủ đề | Nhiệm vụ | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| --- | --- | --- | --- | --- |
| Infrastructure as Code | **CDK Cơ bản – Phần 2** <br> - Tạo hạ tầng bằng AWS CDK <br> - Hiểu về stack và construct <br> - Triển khai hạ tầng bằng CDK CLI <br> - Quản lý tài nguyên CloudFormation | 15/06/2026 | 15/06/2026 | <https://000076.awsstudygroup.com/> |
| Infrastructure as Code | **Giới thiệu về Infrastructure as Code** <br> - Hiểu khái niệm và lợi ích của IaC <br> - So sánh khởi tạo thủ công với triển khai tự động <br> - Học về kiểm soát phiên bản hạ tầng <br> - Cải thiện tính nhất quán khi triển khai | 16/06/2026 | 16/06/2026 | <https://000102.awsstudygroup.com/> |
| Tối ưu EC2 | **Chọn đúng kích thước EC2** <br> - So sánh các họ instance EC2 <br> - Chọn loại instance phù hợp cho từng tải công việc <br> - Cân bằng giữa hiệu năng và chi phí <br> - Áp dụng các phương pháp hay nhất khi chọn kích thước EC2 | 17/06/2026 | 17/06/2026 | <https://000032.awsstudygroup.com/> |
| Giám sát | **Giám sát hạ tầng mạng** <br> - Giám sát hiệu năng mạng bằng CloudWatch <br> - Phân tích các chỉ số mạng <br> - Cấu hình dashboard giám sát <br> - Phát hiện sự cố mạng | 18/06/2026 | 18/06/2026 | <https://000074.awsstudygroup.com/> |
| Thanh toán & IAM | **Ủy quyền truy cập vào bảng điều khiển thanh toán** <br> - Bật quyền truy cập IAM vào Billing Console <br> - Cấp quyền thanh toán một cách an toàn <br> - Áp dụng nguyên tắc đặc quyền tối thiểu | 19/06/2026 | 19/06/2026 | <https://000075.awsstudygroup.com/> |
| Hạn ngạch Dịch vụ | **Yêu cầu tăng hạn ngạch** <br> - Hiểu về AWS Service Quotas <br> - Xác định các giới hạn hạn ngạch <br> - Gửi yêu cầu tăng hạn ngạch | 20/06/2026 | 20/06/2026 | <https://000063.awsstudygroup.com/> |
| Quản lý Chi phí | **Quản lý Sử dụng Tài nguyên và Chi phí bằng IAM trên AWS** <br> - Giám sát mức sử dụng tài nguyên AWS <br> - Kiểm soát truy cập vào thông tin thanh toán bằng IAM <br> - Hiểu các phương pháp hay nhất trong quản lý chi phí <br> - Cải thiện quản trị tài nguyên | 21/06/2026 | 21/06/2026 | <https://000064.awsstudygroup.com/> |

# Thành tựu Tuần 9

## Infrastructure as Code với AWS CDK
- Học các nguyên tắc cơ bản của **Infrastructure as Code (IaC)** và những lợi thế của nó so với việc khởi tạo hạ tầng thủ công.
- Tạo hạ tầng AWS bằng **AWS Cloud Development Kit (CDK)** thông qua việc tổ chức tài nguyên thành các stack và construct.
- Hiểu cách AWS CDK tổng hợp (synthesize) định nghĩa hạ tầng thành các template AWS CloudFormation.
- Triển khai và quản lý tài nguyên đám mây bằng CDK CLI.

## Tự động hóa Hạ tầng
- Hiểu tầm quan trọng của việc kiểm soát phiên bản, tính nhất quán và khả năng triển khai lặp lại của hạ tầng.
- Học cách Infrastructure as Code cải thiện tự động hóa, giảm hiện tượng trôi cấu hình (configuration drift) và đơn giản hóa việc bảo trì hạ tầng.
- So sánh giữa triển khai hạ tầng thủ công và cách tiếp cận khởi tạo tự động.

## Tối ưu Instance EC2
- So sánh các **họ instance Amazon EC2** khác nhau dành cho tải công việc tính toán, bộ nhớ, lưu trữ và mục đích chung.
- Lựa chọn loại instance EC2 phù hợp dựa trên yêu cầu của tải công việc.
- Đánh giá các yếu tố hiệu năng và chi phí khi lựa chọn kích thước instance EC2.
- Áp dụng các phương pháp hay nhất khi chọn kích thước EC2 để tối ưu việc sử dụng tài nguyên đám mây.

## Giám sát Mạng
- Giám sát hạ tầng mạng bằng các chỉ số **Amazon CloudWatch**.
- Theo dõi các chỉ báo hiệu năng mạng để phát hiện các điểm nghẽn tiềm ẩn.
- Cấu hình dashboard giám sát để có khả năng quan sát hạ tầng.
- Nâng cao hiểu biết về giám sát hiệu năng mạng và tình trạng vận hành.

## Quản lý Quyền truy cập Thanh toán
- Bật quyền truy cập cho người dùng IAM vào **AWS Billing Console**.
- Cấu hình quyền thanh toán tuân theo nguyên tắc đặc quyền tối thiểu.
- Hiểu cách ủy quyền truy cập thanh toán giúp cải thiện bảo mật và quản trị tài khoản.

## Hạn ngạch Dịch vụ AWS
- Học cách AWS Service Quotas xác định giới hạn tài nguyên trên các dịch vụ AWS.
- Xác định các giới hạn hạn ngạch có thể ảnh hưởng đến việc triển khai ứng dụng.
- Hiểu quy trình yêu cầu tăng hạn ngạch dịch vụ khi cần thêm dung lượng.

## Giám sát Sử dụng Tài nguyên và Quản lý Chi phí
- Khám phá việc giám sát sử dụng tài nguyên AWS và các phương pháp quản lý chi phí đám mây.
- Hiểu cách quyền IAM giúp bảo vệ tài nguyên thanh toán và quản lý chi phí.
- Học các phương pháp hay nhất để giám sát mức sử dụng tài nguyên AWS và kiểm soát chi phí đám mây.
- Nâng cao nhận thức về các chiến lược quản trị nhằm quản lý tài nguyên AWS hiệu quả.

### Tóm tắt lý thuyết

- **Infrastructure as Code (IaC):** Phương pháp quản lý và khởi tạo hạ tầng thông qua mã nguồn thay vì cấu hình thủ công.
- **AWS CDK:** Framework phát triển cho phép định nghĩa hạ tầng đám mây bằng ngôn ngữ lập trình và triển khai thông qua AWS CloudFormation.
- **Loại Instance Amazon EC2:** Các họ instance khác nhau được thiết kế cho tải công việc mục đích chung, tối ưu tính toán, tối ưu bộ nhớ, tối ưu lưu trữ và các tải công việc chuyên biệt.
- **Amazon CloudWatch:** Dịch vụ giám sát dùng để thu thập số liệu, log và cảnh báo cho tài nguyên AWS.
- **AWS Billing Console:** Bảng điều khiển tập trung để xem thông tin sử dụng, thanh toán và quản lý chi phí AWS.
- **AWS Service Quotas:** Giới hạn dịch vụ xác định số lượng tài nguyên AWS tối đa có sẵn trong một tài khoản hoặc Region.
- **IAM cho Quản lý Chi phí:** Chính sách IAM có thể được sử dụng để ủy quyền truy cập an toàn vào tài nguyên thanh toán và quản lý chi phí, tuân theo nguyên tắc đặc quyền tối thiểu.
