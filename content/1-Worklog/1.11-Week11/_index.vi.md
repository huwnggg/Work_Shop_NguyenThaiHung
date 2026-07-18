---
title: "Worklog Tuần 11"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.11. </b> "
---

### Mục tiêu tuần 11:
* Triển khai cụm máy chủ Web/App EC2 và cân bằng tải Application Load Balancer (ALB) cho dự án Genzite.
* Cấu hình nhóm co giãn tự động Auto Scaling Group (ASG) để tự động hóa điều phối số lượng instances.
* Thiết lập quản lý tên miền Route 53 và cấp chứng chỉ bảo mật SSL/TLS qua AWS Certificate Manager (ACM).
* Phân phối ứng dụng qua Amazon CloudFront CDN để tăng tốc độ tải trang toàn cầu.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| Thứ Hai | **Khởi chạy máy chủ ảo EC2 & Launch Template** <br>- Khởi chạy máy chủ EC2 cài đặt Docker và cấu hình chạy mã nguồn Genzite. <br>- Đóng gói cấu hình máy chủ tạo Launch Template phục vụ việc nhân bản. | 29/06/2026 | 29/06/2026 | [EC2 Web Server](../../../aws-workshop-genzite.md#L1048) |
| Thứ Ba | **Thiết lập Application Load Balancer (ALB)** <br>- Tạo lập Application Load Balancer và cấu hình Target Group để cân bằng tải. <br>- Định tuyến các yêu cầu HTTP (cổng 80) đến các máy chủ EC2 Web. | 30/06/2026 | 30/06/2026 | [Load Balancer Setup](../../../aws-workshop-genzite.md#L1120) |
| Thứ Tư | **Cấu hình Auto Scaling Group (ASG)** <br>- Khởi tạo Auto Scaling Group tự động co giãn số lượng máy chủ dựa trên nhu cầu sử dụng thực tế. <br>- Kiểm tra chính sách co giãn tự động để đảm bảo tính sẵn sàng cao (HA). | 01/07/2026 | 01/07/2026 | [Auto Scaling Group](../../../aws-workshop-genzite.md#L1190) |
| Thứ Năm | **Cấu hình ACM SSL/TLS & Quản trị Route 53** <br>- Đăng ký và yêu cầu cấp chứng chỉ bảo mật SSL/TLS miễn phí qua ACM. <br>- Tạo các Record Set trên Route 53 để trỏ tên miền về địa chỉ ALB giúp phân giải HTTPS an toàn. | 02/07/2026 | 02/07/2026 | [Route 53 & ACM](../../../aws-workshop-genzite.md#L1254) |
| Thứ Sáu | **Cấu hình mạng phân phối nội dung CloudFront** <br>- Khởi tạo CloudFront Distribution để phân phối mã nguồn frontend (S3) và ứng dụng dynamic (ALB). <br>- Tối ưu hóa phân phối, kích hoạt bộ đệm cache tại các Edge locations. | 03/07/2026 | 03/07/2026 | [CloudFront Distribution](../../../aws-workshop-genzite.md#L1390) |

### Kết quả đạt được tuần 11:
* Triển khai thành công nhóm máy chủ EC2 Web đặt sau Application Load Balancer và Auto Scaling Group.
* Đảm bảo hệ thống tự động co giãn và tự phục hồi khi có máy chủ gặp sự cố trong hệ thống Genzite.
* Kích hoạt giao thức bảo mật HTTPS an toàn thông qua việc tích hợp chứng chỉ ACM và dịch vụ định tuyến Route 53.
* Phân phối ứng dụng thành công qua CloudFront CDN giúp giảm thiểu độ trễ tải trang cho người dùng cuối.
