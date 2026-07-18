---
title: "Worklog Tuần 12"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.12. </b> "
---

### Mục tiêu tuần 12:
* Tự động hóa quy trình CI/CD cho dự án Genzite thông qua công cụ Jenkins.
* Thiết lập các giải pháp bảo mật nâng cao Bastion Host, SSM Session Manager và AWS WAF/Shield.
* Cấu hình giám sát hoạt động hệ thống bằng Amazon CloudWatch.
* Tiến hành tự đánh giá (Self-assessment), hoàn thiện báo cáo thực tập và dọn dẹp sạch sẽ tài nguyên.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| Thứ Hai | **Tự động hóa CI/CD với Jenkins Pipeline** <br>- Thiết lập máy chủ Jenkins và viết Jenkinsfile tự động hóa quá trình kéo code, build và deploy ứng dụng Genzite. | 06/07/2026 | 06/07/2026 | [Jenkins CI/CD Pipeline](../../../aws-workshop-genzite.md#L1491) |
| Thứ Ba | **Bảo mật truy cập với Bastion Host & SSM Session Manager** <br>- Khởi tạo máy chủ Bastion Host trong Public Subnet để làm cầu nối truy cập an toàn. <br>- Cấu hình Systems Manager Session Manager để kết nối SSH an toàn vào EC2 không cần mở port SSH. | 07/07/2026 | 07/07/2026 | [Bastion Host & SSM](../../../aws-workshop-genzite.md#L1739) |
| Thứ Tư | **Cấu hình Giám sát hệ thống qua CloudWatch** <br>- Cấu hình CloudWatch Metrics, Alarms, Logs Insights để theo dõi sức khỏe và hiệu năng của cụm Web server, Database và Cache. | 08/07/2026 | 08/07/2026 | [CloudWatch Monitoring](../../../aws-workshop-genzite.md#L1824) |
| Thứ Năm | **Kích hoạt bảo mật mạng AWS WAF & Shield** <br>- Tạo các quy tắc Web ACL trên AWS WAF để bảo vệ website Genzite khỏi các tấn công web phổ biến (SQL injection, XSS) và DDoS. | 09/07/2026 | 09/07/2026 | [WAF & Shield Security](../../../aws-workshop-genzite.md#L1913) |
| Thứ Sáu | **Dọn dẹp hệ thống & Hoàn thiện báo cáo thực tập** <br>- Thực hiện dọn dẹp (Cleanup) toàn bộ hạ tầng đã cấu hình trên AWS để tránh phát sinh cước phí sau thực tập. <br>- Tiến hành tự đánh giá kết quả thực tập (Self-assessment) và hoàn thiện website nhật ký công việc. | 10/07/2026 | 10/07/2026 | [Genzite Cleanup](../../../aws-workshop-genzite.md#L1963) <br>[Self-assessment](../../6-Self-evaluation/) |

### Kết quả đạt được tuần 12:
* Xây dựng thành công quy trình CI/CD tự động kiểm thử và deploy ứng dụng qua Jenkins Pipeline.
* Hạn chế tối đa rủi ro bảo mật thông qua việc cô lập mạng và quản trị EC2 bằng SSM Session Manager.
* Đảm bảo tính minh bạch hoạt động qua các bảng Dashboard theo dõi lưu lượng và log tập trung của CloudWatch.
* Bảo vệ an toàn ứng dụng web bằng hệ thống tường lửa ứng dụng AWS WAF.
* Dọn dẹp triệt để 100% tài nguyên đã tạo trong Capstone Project và hoàn thiện trang web báo cáo thực tập đúng thời hạn.
