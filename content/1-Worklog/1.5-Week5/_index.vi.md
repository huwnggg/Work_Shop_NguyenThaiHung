---
title: "Worklog Tuần 5"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.5. </b> "
---

### Mục tiêu tuần 5:
* Tìm hiểu dịch vụ cơ sở dữ liệu quan hệ Amazon RDS và cách thiết lập môi trường mạng (VPC, DB Subnet Group, Security Group).
* Thực hành khởi tạo Database Instance trên Amazon RDS và triển khai ứng dụng kết nối trực tiếp.
* Nghiên cứu cơ sở dữ liệu NoSQL Amazon DynamoDB bao gồm Primary Key, Secondary Index và thực hành qua CloudShell/Console/SDK Python.
* Tối ưu hiệu năng dữ liệu bằng giải pháp bộ nhớ đệm (Amazon ElastiCache Redis Cluster).
* Thiết lập sao lưu dữ liệu (Backup & Restore) trên RDS và dọn dẹp (Cleanup) tài nguyên ở cả 3 bài lab (RDS, DynamoDB, ElastiCache).

### Các công việc cần triển khai trong tuần này:
| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| Thứ Sáu | **Ngày 1: Cơ sở dữ liệu quan hệ (Amazon RDS) - Tổng quan & Chuẩn bị** <br>- Tìm hiểu tổng quan Amazon RDS cho các tác vụ xử lý giao dịch (OLTP). <br>- Thực hành chuẩn bị môi trường mạng: tạo VPC, DB Subnet Group và cấu hình Security Group. | 15/05/2026 | 15/05/2026 | [RDS Intro](https://000005.awsstudygroup.com/1-introduce/) <br>[RDS Networking](https://000005.awsstudygroup.com/2-prerequiste/) |
| Thứ Bảy - CN | **Ngày 2: Triển khai Amazon RDS và Ứng dụng** <br>- Thực hành tạo máy chủ EC2 và khởi tạo Database Instance trên Amazon RDS. <br>- Triển khai ứng dụng (Application Deployment) để kết nối trực tiếp vào cơ sở dữ liệu RDS. | 16/05/2026 | 17/05/2026 | [RDS Database Creation](https://000005.awsstudygroup.com/4-create-rds/) <br>[Deploy App](https://000005.awsstudygroup.com/5-deploy-app/) |
| Thứ Hai | **Ngày 3: Cơ sở dữ liệu phi quan hệ (Amazon DynamoDB) - Kiến thức cốt lõi** <br>- Nghiên cứu DynamoDB cho dữ liệu phi cấu trúc: Primary Key, Secondary Index và chế độ Read/Write Capacity. <br>- Thực hành tạo bảng, ghi và truy vấn dữ liệu trực tiếp trên Console và CloudShell. | 18/05/2026 | 18/05/2026 | [DynamoDB Intro](https://000060.awsstudygroup.com/1-introduce/) <br>[Console/CloudShell Labs](https://000060.awsstudygroup.com/2-prerequiste/) |
| Thứ Ba | **Ngày 4: Tương tác DynamoDB thông qua AWS SDK (Python)** <br>- Cấu hình AWS CLI và sử dụng thư viện AWS SDK Python (Boto3) để tự động hóa tạo bảng, ghi, đọc, cập nhật và quét (scan) dữ liệu trên DynamoDB. | 19/05/2026 | 19/05/2026 | [AWS SDK Python](https://000060.awsstudygroup.com/3-gettingstartedwithawssdk/3.2-pythonandynamodb/) |
| Thứ Tư | **Ngày 5: Tối ưu hiệu năng với Bộ nhớ đệm (Amazon ElastiCache Redis)** <br>- Tìm hiểu ElastiCache Redis giúp giảm tải database. <br>- Thực hành chuẩn bị CLI, tạo Subnet Group, khởi tạo ElastiCache Cluster (bật/tắt Cluster mode) và kết nối tới các Node. | 20/05/2026 | 20/05/2026 | [ElastiCache Prep](https://000061.awsstudygroup.com/2-prerequiste/) <br>[Create Redis Cluster](https://000061.awsstudygroup.com/3-amazonelasticacheforredis/) |
| Thứ Năm | **Ngày 6: Đọc và ghi dữ liệu trên ElastiCache bằng SDK** <br>- Thực hành sử dụng AWS SDK để kết nối vào ElastiCache. <br>- Chạy lệnh Set/Get chuỗi dữ liệu (strings), thao tác với hash, Publish/Subscribe và làm việc với Stream. | 21/05/2026 | 21/05/2026 | [SDK ElastiCache](https://000061.awsstudygroup.com/4-sdkelasticache/) |
| Thứ Sáu | **Ngày 7: Sao lưu (Backup) và Dọn dẹp tài nguyên (Clean up)** <br>- Thực hành sao lưu và phục hồi (Backup and Restore) trên Amazon RDS. <br>- Thực hiện dọn dẹp sạch sẽ toàn bộ tài nguyên đã tạo ở cả 3 bài lab (RDS, DynamoDB, ElastiCache) để tránh phát sinh chi phí. | 22/05/2026 | 22/05/2026 | [RDS Backup](https://000005.awsstudygroup.com/6-backup/) <br>[RDS Cleanup](https://000005.awsstudygroup.com/7-cleanup/) <br>[DynamoDB Cleanup](https://000060.awsstudygroup.com/4-cleanupresource/) <br>[ElastiCache Cleanup](https://000061.awsstudygroup.com/5.cleanupresource/) |

### Kết quả đạt được tuần 5:
* Làm chủ quy trình tạo lập, phân tách mạng an toàn và kết nối ứng dụng thực tế tới Amazon RDS PostgreSQL.
* Hiểu rõ cơ chế thiết kế cấu trúc bảng và chỉ mục tối ưu trên DynamoDB NoSQL, thực thi truy cập dữ liệu thành thạo bằng thư viện SDK Python.
* Triển khai thành công cụm đệm ElastiCache Redis, kết nối trực tiếp đến các Node và thực thi các kiểu dữ liệu nâng cao (Hash, Pub/Sub, Stream) qua SDK.
* Thực hành thành công tính năng Backup/Restore trên RDS đảm bảo tính dự phòng thảm họa cho dữ liệu.
* Hoàn thành dọn dẹp sạch sẽ 100% các tài nguyên RDS, DynamoDB, và ElastiCache sau khi kết thúc chuỗi bài thực hành.
