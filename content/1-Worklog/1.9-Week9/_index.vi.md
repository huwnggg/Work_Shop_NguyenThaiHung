---
title: "Worklog Tuần 9"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.9. </b> "
---

### Mục tiêu tuần 9:
* Tìm hiểu cách vận hành và tối ưu các ứng dụng chạy trên nền tảng Windows Server trên hạ tầng đám mây AWS.
* Nghiên cứu dịch vụ quản lý thư mục tập trung AWS Managed Microsoft AD và cơ chế gia nhập miền (Domain Join).
* Thực hành thiết kế kiến trúc hệ thống ứng dụng Web hoàn chỉnh có tính sẵn sàng cao (Highly Available) và khả năng chống chịu lỗi (Fault-Tolerant).
* Triển khai bài tập tổng hợp kết hợp các dịch vụ cốt lõi: VPC, EC2, Auto Scaling, RDS, S3, Route 53, và CloudFront.
* Hoàn thành dọn dẹp sạch sẽ tài nguyên kiểm thử để tối ưu ngân sách AWS Free Tier.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| Thứ Hai | **Vận hành ứng dụng Windows & AWS Managed Microsoft AD** <br>- Tìm hiểu kiến thức nền tảng về cách vận hành hệ điều hành Windows Server trên AWS. <br>- Nghiên cứu dịch vụ AWS Managed Microsoft AD và phương thức quản trị tài khoản/thư mục tập trung. | 15/06/2026 | 15/06/2026 | AWS Windows on AWS Guide |
| Thứ Ba | **Thực hành triển khai Active Directory & Domain Join** <br>- Khởi tạo AWS Managed Microsoft AD Cluster trong VPC. <br>- Khởi chạy máy chủ EC2 Windows Server và thực hiện cấu hình gia nhập miền (Domain Join) tự động/thủ công. | 16/06/2026 | 16/06/2026 | AWS Directory Service Labs |
| Thứ Tư | **Thiết kế kiến trúc hệ thống Web HA/Fault-Tolerant** <br>- Phân tích và thiết kế sơ đồ ứng dụng web 3 lớp có tính sẵn sàng cao và chống chịu lỗi tốt. <br>- Lập kế hoạch chia subnets đa vùng (Multi-AZ), cấu hình Target Group và Application Load Balancer. | 17/06/2026 | 17/06/2026 | AWS Architecture Framework |
| Thứ Năm | **Bài tập tổng kết - Triển khai hạ tầng Web & Data (EC2, ASG, RDS, S3)** <br>- Triển khai cơ sở dữ liệu Amazon RDS PostgreSQL đa vùng và S3 bucket lưu trữ asset tĩnh. <br>- Cấu hình Launch Template và khởi chạy Auto Scaling Group tự động co giãn máy chủ EC2 Web Server theo tải. | 18/06/2026 | 18/06/2026 | AWS Web App Deployment Guide |
| Thứ Sáu | **Bài tập tổng kết - Cấu hình CloudFront, Route 53 & Dọn dẹp hệ thống** <br>- Tạo mạng phân phối nội dung CloudFront trỏ về ALB/S3, cấu hình định tuyến tên miền qua Route 53. <br>- Kiểm tra khả năng chịu lỗi (failover) và thực hiện xóa toàn bộ tài nguyên để tránh phát sinh chi phí ngoài ý muốn. | 19/06/2026 | 19/06/2026 | AWS Integration Labs |

### Kết quả đạt được tuần 9:
* Hiểu rõ cách vận hành ứng dụng Windows Server và quản trị thư mục người dùng tập trung thông qua AWS Managed Microsoft AD.
* Tự thiết kế và hiện thực hóa thành công sơ đồ kiến trúc hạ tầng Web-App 3 lớp có khả năng phục hồi lỗi cao.
* Phối hợp nhuần nhuyễn các dịch vụ VPC, EC2, Auto Scaling, RDS, S3, Route 53 và CloudFront để tạo nên hệ thống hoàn chỉnh.
* Biết cách cấu hình CloudFront CDN làm lá chắn bảo mật và Route 53 làm công cụ phân giải tên miền thông minh.
* Dọn dẹp sạch sẽ 100% tài nguyên sau bài lab tổng kết đảm bảo kiểm soát chi phí hiệu quả.
