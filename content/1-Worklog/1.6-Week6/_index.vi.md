---
title: "Worklog Tuần 6"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.6. </b> "
---

### Mục tiêu tuần 6:
* Tìm hiểu và triển khai Docker containers đơn giản trên dịch vụ Amazon Lightsail.
* Tự đóng gói (build), đẩy lên (push) và triển khai container image tùy chỉnh trên Amazon Lightsail.
* Xây dựng kiến trúc web có tính sẵn sàng cao bằng Elastic Load Balancing (ELB) và Auto Scaling Group (ASG) trên EC2 và RDS.
* Cấu hình giám sát hiệu năng CPU/RAM và phân tích logs tập trung bằng Amazon CloudWatch Metrics & Logs.
* Thiết lập hệ thống cảnh báo tự động (CloudWatch Alarms) và thiết kế giao diện theo dõi sức khỏe hệ thống (CloudWatch Dashboards).
* Thực hiện dọn dẹp (Cleanup) sạch sẽ toàn bộ tài nguyên đã tạo để tránh phát sinh chi phí ngoài ý muốn.

### Các công việc cần triển khai trong tuần này:
| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| Thứ Sáu | **Ngày 1: Amazon Lightsail - Khởi tạo & Triển khai Container cơ bản** <br>- Tìm hiểu dịch vụ Amazon Lightsail Containers để chạy ứng dụng trên container đơn giản. <br>- Thực hành tạo dịch vụ Container (Container Service) và triển khai thử một Public Docker Image. | 22/05/2026 | 22/05/2026 | [Lightsail Prep](https://000046.awsstudygroup.com/1-prepare/) <br>[Deploy Public Image](https://000046.awsstudygroup.com/3-deploy-publicimage/) |
| Thứ Bảy - CN | **Ngày 2: Amazon Lightsail - Triển khai Container Image tùy chỉnh** <br>- Khởi tạo máy chủ Ubuntu trên Lightsail, cài đặt Docker và AWS CLI. <br>- Tự build Docker image cá nhân, push lên Lightsail Container Service và thực hiện deploy. | 23/05/2026 | 24/05/2026 | [Deploy Custom Image](https://000046.awsstudygroup.com/4-deploy-yourimage/) |
| Thứ Hai | **Ngày 3: Auto Scaling & ELB - Chuẩn bị hạ tầng & Load Balancer** <br>- Chuẩn bị hạ tầng gồm VPC, EC2, RDS PostgreSQL, Web Server và Launch Template. <br>- Khởi tạo Elastic Load Balancer (Target Group & Application Load Balancer) để cân bằng tải. | 25/05/2026 | 25/05/2026 | [Infra Prep](https://000006.awsstudygroup.com/2-preparation/) <br>[ALB Setup](https://000006.awsstudygroup.com/4-setup-load-balancer/) |
| Thứ Ba | **Ngày 4: Auto Scaling & ELB - Thiết lập Auto Scaling và Kiểm thử** <br>- Khởi tạo Auto Scaling Group tự động co giãn số lượng máy chủ EC2 theo tải thực tế. <br>- Kiểm thử (Test) các giải pháp co giãn: manual, scheduled, dynamic, và predictive scaling. | 26/05/2026 | 26/05/2026 | [ASG Setup](https://000006.awsstudygroup.com/6-create-auto-scaling-group/) <br>[Scaling Test](https://000006.awsstudygroup.com/7-test-solutions/) |
| Thứ Tư | **Ngày 5: Amazon CloudWatch - Giám sát hiệu năng & Thu thập Logs** <br>- Tìm hiểu CloudWatch Metrics, thực hiện các biểu thức toán học và tìm kiếm chỉ số. <br>- Cấu hình thu thập logs tập trung về CloudWatch Logs (tra cứu qua Logs Insights và tạo Metric Filter). | 27/05/2026 | 27/05/2026 | [CloudWatch Metrics](https://000008.awsstudygroup.com/3-cloud-watch-metric/) <br>[CloudWatch Logs](https://000008.awsstudygroup.com/4-cloud-watch-logs/) |
| Thứ Năm | **Ngày 6: Amazon CloudWatch - Cấu hình Cảnh báo & Bảng điều khiển** <br>- Tạo các cảnh báo tự động CloudWatch Alarms để gửi mail khi có sự cố giúp giảm chỉ số MTTR. <br>- Thiết lập bảng điều khiển Dashboards trực quan giám sát toàn diện sức khỏe hệ thống. | 28/05/2026 | 28/05/2026 | [CloudWatch Alarms](https://000008.awsstudygroup.com/5-cloud-watch-alarm/) <br>[CloudWatch Dashboards](https://000008.awsstudygroup.com/6-cloud-watch-dashboard/) |
| Thứ Sáu | **Ngày 7: Dọn dẹp hệ thống (Cleanup Resources)** <br>- Thực hiện xóa bỏ toàn bộ các tài nguyên đã cấu hình ở cả 3 bài thực hành (Lightsail, EC2/ASG/ALB/RDS, CloudWatch) để tránh phát sinh chi phí phát sinh. | 29/05/2026 | 29/05/2026 | [Lightsail Cleanup](https://000046.awsstudygroup.com/5-clean-up/) <br>[Auto Scaling Cleanup](https://000006.awsstudygroup.com/8-cleanup/) <br>[CloudWatch Cleanup](https://000008.awsstudygroup.com/7-clean-up-resources/) |

### Kết quả đạt được tuần 6:
* Hiểu rõ cách đóng gói và vận hành Docker containers nhanh chóng trên môi trường Amazon Lightsail.
* Thiết lập thành công hạ tầng Web-App chịu lỗi cao nhờ ứng dụng cân bằng tải ALB và co giãn tự động Auto Scaling Group.
* Làm chủ các kỹ thuật cấu hình cảnh báo, thu thập metric hiệu năng và truy vấn log tập trung thông qua CloudWatch Logs Insights.
* Thiết kế được bảng điều khiển CloudWatch Dashboards giám sát sức khỏe toàn diện của hạ tầng cloud theo thời gian thực.
* Hoàn tất dọn dẹp sạch sẽ toàn bộ tài nguyên thừa từ cả ba bài thực hành nhằm kiểm soát chi phí tối ưu.
