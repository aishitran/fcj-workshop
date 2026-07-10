---
title: "Nhật ký công việc Tuần 8"
date: 08/06/2026
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
---

### Mục tiêu Tuần 8:

* Thành thạo chiến lược gắn thẻ (tagging) tài nguyên để tổ chức và theo dõi chi phí.
* Học các kỹ thuật IAM nâng cao sử dụng thẻ tài nguyên để kiểm soát truy cập chi tiết.
* Hiểu về AWS Systems Manager để quản lý hạ tầng ở quy mô lớn.
* Học quản lý phiên (session) và truy cập từ xa vào EC2 instance.

### Các nhiệm vụ thực hiện trong tuần:

| Chủ đề | Nhiệm vụ | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| --- | --- | --- | --- | --- |
| Quản lý Tài nguyên | **Quản lý Tài nguyên bằng Thẻ và Nhóm Tài nguyên** <br> - Triển khai chiến lược gắn thẻ <br> - Tổ chức tài nguyên bằng thẻ <br> - Tạo nhóm tài nguyên theo thẻ <br> - Theo dõi chi phí bằng thẻ | 08/06/2026 | 08/06/2026 | <https://000027.awsstudygroup.com/> |
| Kiểm soát Truy cập Chi tiết | **Quản lý Truy cập vào Dịch vụ EC2 bằng Thẻ Tài nguyên thông qua IAM** <br> - Tạo chính sách IAM dựa trên thẻ <br> - Kiểm soát truy cập tài nguyên bằng thẻ <br> - Triển khai kiểm soát truy cập theo môi trường (dev, staging, prod) <br> - Kiểm tra các mẫu truy cập dựa trên thẻ | 09/06/2026 | 09/06/2026 | <https://000028.awsstudygroup.com/> |
| Quản lý Hạ tầng | **Quản lý Bản vá và Chạy Lệnh trên Nhiều Máy chủ với AWS Systems Manager** <br> - Thiết lập agent Systems Manager <br> - Tạo chính sách vá lỗi và nhóm vá lỗi <br> - Chạy lệnh trên nhiều instance <br> - Giám sát mức độ tuân thủ bản vá | 10/06/2026 | 10/06/2026 | <https://000031.awsstudygroup.com/> |
| Truy cập từ xa | **Làm việc với Amazon Systems Manager - Session Manager** <br> - Cấu hình Session Manager để truy cập EC2 an toàn <br> - Tạo vai trò IAM cho Session Manager <br> - Thiết lập phiên làm việc không cần khóa SSH <br> - Giám sát và ghi log hoạt động phiên | 11/06/2026 | 11/06/2026 | <https://000058.awsstudygroup.com/> |

# Thành tựu Tuần 8

## Chiến lược Gắn thẻ Tài nguyên
- Triển khai **chiến lược gắn thẻ toàn diện** phân loại tài nguyên theo môi trường (dev/staging/prod), dự án, chủ sở hữu, trung tâm chi phí và ứng dụng.
- Tổ chức **kho tài nguyên quy mô lớn** bằng thẻ, giúp tài nguyên dễ dàng được tìm thấy và quản lý.
- Tạo **nhóm tài nguyên** dựa trên bộ lọc thẻ để tổ chức hợp lý và thực hiện thao tác hàng loạt.
- Sử dụng **thẻ để phân bổ chi phí**, cho phép quy trách nhiệm chi phí (chargeback) và theo dõi chi tiết theo đơn vị kinh doanh, dự án hoặc môi trường.

## Kiểm soát Truy cập Chi tiết bằng Thẻ
- Tạo **chính sách IAM dựa trên thẻ** cho phép cấp quyền dựa trên thẻ tài nguyên thay vì tên tài nguyên hay ARN.
- Triển khai **kiểm soát truy cập theo môi trường**: nhà phát triển chỉ truy cập tài nguyên dev, QA truy cập staging, bộ phận vận hành truy cập production.
- Sử dụng các **khóa điều kiện (condition key)** như `aws:PrincipalTag` và `aws:ResourceTag` để quản lý quyền một cách linh hoạt và có khả năng mở rộng.
- Kiểm tra **các mẫu truy cập dựa trên thẻ** để đảm bảo chính sách bảo mật được thực thi đúng và phát hiện các bất thường.

## Quản lý Hạ tầng ở Quy mô Lớn
- Thiết lập **agent Systems Manager** trên các EC2 instance để có khả năng quản lý và tự động hóa.
- Tạo **chính sách vá lỗi** xác định lịch trình vá lỗi và nhóm vá lỗi để quản lý bản vá có tổ chức.
- Thực thi **Run Command** để chạy script và lệnh trên nhiều instance cùng lúc, giảm công sức cấu hình thủ công.
- Giám sát **mức độ tuân thủ bản vá** và tạo báo cáo cho biết instance nào đã được cập nhật các bản vá bảo mật.

## Truy cập Từ xa An toàn với Session Manager
- Cấu hình **Session Manager** như một giải pháp thay thế an toàn cho SSH, loại bỏ nhu cầu quản lý khóa SSH.
- Tạo **vai trò IAM có quyền Session Manager** để kiểm soát truy cập chi tiết đến từng instance riêng lẻ.
- Thiết lập **phiên làm việc đến EC2 instance** thông qua AWS console hoặc CLI mà không cần mở instance ra internet.
- Bật **ghi log và giám sát phiên làm việc** trong CloudTrail và CloudWatch để phục vụ kiểm toán và tuân thủ.

### Tóm tắt lý thuyết
- **Thẻ Tài nguyên (Resource Tags)**: Cặp khóa-giá trị gắn vào tài nguyên AWS để phục vụ tổ chức, tự động hóa và phân bổ chi phí.
- **Chiến lược Gắn thẻ**: Phương pháp tiếp cận có hệ thống trong việc gắn thẻ, xác định các chiều (môi trường, dự án, chủ sở hữu, trung tâm chi phí, v.v.) để quản lý tài nguyên nhất quán.
- **Chính sách IAM dựa trên Thẻ**: Kiểm soát truy cập dựa trên điều kiện sử dụng thẻ tài nguyên và thẻ chủ thể (principal), cho phép quản lý quyền có khả năng mở rộng mà không cần mã hóa cứng ARN tài nguyên.
- **Systems Manager**: Dịch vụ AWS trung tâm để quản lý hạ tầng bao gồm vá lỗi, tự động hóa và truy cập từ xa.
- **Session Manager**: Công cụ truy cập từ xa an toàn cung cấp quyền truy cập shell vào EC2 instance mà không cần khóa SSH, với đầy đủ khả năng ghi log kiểm toán.
