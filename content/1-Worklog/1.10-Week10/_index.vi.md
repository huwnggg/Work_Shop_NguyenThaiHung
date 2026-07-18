---
title: "Worklog Tuần 10"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.10. </b> "
---

### Mục tiêu tuần 10:
* Khởi động dự án Capstone Genzite: Nghiên cứu kiến trúc hệ thống và quy hoạch tài nguyên.
* Triển khai hạ tầng mạng cơ bản (VPC, Subnets, Route Tables, Internet Gateway, NAT Gateway).
* Thiết lập bảo mật an toàn với IAM Roles (`GenziteEC2Role`) và cấu hình Security Groups cho các lớp ứng dụng.
* Khởi tạo các dịch vụ lưu trữ đối tượng và cơ sở dữ liệu cốt lõi (S3 Frontend/Media, RDS PostgreSQL, ElastiCache Redis).

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| Thứ Hai | **Khởi động Capstone Genzite & Cấu hình IAM Role** <br>- Nghiên cứu sơ đồ kiến trúc tổng quan của hệ thống Genzite. <br>- Tạo và cấu hình IAM Role `GenziteEC2Role` để cho phép máy chủ EC2 giao tiếp an toàn với các dịch vụ AWS. | 22/06/2026 | 22/06/2026 | [Genzite Architecture](../../../aws-workshop-genzite.md#L552) |
| Thứ Ba | **Thiết lập hạ tầng mạng VPC & Subnets** <br>- Tạo VPC, phân chia dải IP, thiết lập Public/Private Subnets nằm trên các Availability Zones khác nhau. <br>- Cấu hình Internet Gateway, NAT Gateway và cập nhật Route Tables chính xác. | 23/06/2026 | 23/06/2026 | [Genzite VPC Setup](../../../aws-workshop-genzite.md#L628) |
| Thứ Tư | **Khởi tạo dịch vụ lưu trữ S3 Frontend & Media** <br>- Tạo lập S3 Frontend bucket phục vụ lưu trữ code giao diện và S3 Media bucket chứa tệp đa phương tiện. <br>- Thiết lập cấu hình CORS rules và Block Public Access an toàn. | 24/06/2026 | 24/06/2026 | [S3 Buckets Setup](../../../aws-workshop-genzite.md#L754) |
| Thứ Năm | **Cấu hình Cơ sở dữ liệu quan hệ RDS PostgreSQL** <br>- Khởi tạo cơ sở dữ liệu Amazon RDS PostgreSQL Database Instance trong Private Subnet. <br>- Cấu hình DB Subnet Group và thiết lập Security Group cho phép kết nối an toàn từ máy chủ Web. | 25/06/2026 | 25/06/2026 | [RDS Database Setup](../../../aws-workshop-genzite.md#L836) |
| Thứ Sáu | **Triển khai Amazon ElastiCache Redis Cluster** <br>- Khởi tạo cụm đệm dữ liệu Amazon ElastiCache for Redis Cluster. <br>- Cấu hình Security Group cô lập và tối ưu hóa luồng dữ liệu cache cho ứng dụng Genzite. | 26/06/2026 | 26/06/2026 | [Redis Cache Setup](../../../aws-workshop-genzite.md#L947) |

### Kết quả đạt được tuần 10:
* Nắm vững cấu trúc kiến trúc tổng quan và chuẩn bị đầy đủ chính sách IAM cho dự án Genzite.
* Tự tay xây dựng thành công hạ tầng mạng VPC bảo mật nhiều lớp làm nền tảng cho hệ thống.
* Triển khai xuất sắc S3 Frontend & Media Buckets tích hợp các chính sách CORS phục vụ ứng dụng.
* Cài đặt ổn định cơ sở dữ liệu quan hệ RDS PostgreSQL và bộ nhớ đệm ElastiCache Redis Cluster trong mạng nội bộ.
