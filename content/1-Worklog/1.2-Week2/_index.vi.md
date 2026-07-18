---
title: "Worklog Tuần 2"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.2. </b> "
---

### Mục tiêu tuần 2:
* Tìm hiểu và nắm vững kiến thức nền tảng về Amazon VPC (Subnet, Route Table, IGW, NAT Gateway, Security Groups, NACLs).
* Thực hành xây dựng thủ công môi trường mạng VPC và thiết lập giám sát bằng VPC Flow Logs.
* Triển khai máy chủ EC2 an toàn, kiểm tra kết nối mạng qua Reachability Analyzer và quản trị qua SSM Session Manager.
* Cấu hình giả lập kết nối AWS Site-to-Site VPN để thiết lập kênh kết nối an toàn VPN Tunnel.
* Tiếp cận phương pháp tự động hóa hạ tầng (IaC) qua CloudFormation và thực hành dọn dẹp tài nguyên tối ưu chi phí.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| Thứ Hai | **Lý thuyết VPC & Bảo mật mạng** <br>- Tìm hiểu các khái niệm cốt lõi của VPC: Subnets, Route Table, Internet Gateway, NAT Gateway. <br>- Nghiên cứu tường lửa trong VPC (Security Groups, Network ACLs) và bản đồ tài nguyên VPC Resource Map. | 27/04/2026 | 27/04/2026 | [VPC Intro](https://000003.awsstudygroup.com/1-introduce/) <br>[VPC Security](https://000003.awsstudygroup.com/2-firewallinvpc/) |
| Thứ Ba | **Thiết lập môi trường VPC & Flow Logs** <br>- Thực hành tạo lập VPC, Subnets, Internet Gateway, Route Tables và Security Groups. <br>- Bật tính năng ghi log luồng mạng VPC Flow Logs để giám sát và ghi lại traffic. | 28/04/2026 | 28/04/2026 | [Network Prep](https://000003.awsstudygroup.com/3-prerequisite/) |
| Thứ Tư | **Triển khai máy chủ EC2 & Giám sát** <br>- Khởi tạo máy chủ EC2 trong VPC, kiểm tra kết nối internet qua NAT Gateway. <br>- Quản trị EC2 an toàn không cần SSH key qua AWS Systems Manager Session Manager. <br>- Kiểm tra đường truyền qua Reachability Analyzer và giám sát qua CloudWatch. | 29/04/2026 | 29/04/2026 | [EC2 Deployment](https://000003.awsstudygroup.com/4-createec2server/) |
| Thứ Năm | **Cấu hình AWS Site-to-Site VPN & Tự động hóa IaC** <br>- Xây dựng môi trường giả lập VPN: tạo CGW, VGW và cấu hình kênh truyền bảo mật VPN Tunnel. <br>- Tìm hiểu mở rộng VPN sử dụng Strongswan với Transit Gateway. <br>- Nghiên cứu triển khai hạ tầng tự động hóa sử dụng các mẫu Infrastructure as Code (IaC) CloudFormation. | 30/04/2026 | 30/04/2026 | [AWS VPN Setup](https://000003.awsstudygroup.com/5-vpnsitetosite/) <br>[Strongswan VPN](https://000003.awsstudygroup.com/5-vpnsitetosite/5.3-vpnsitetosite-optional/) <br>[IaC CloudFormation](https://000003.awsstudygroup.com/7-infrastructureascode/) |
| Thứ Sáu | **Dọn dẹp tài nguyên & Đánh giá Best Practices** <br>- Thực hiện các bước xóa bỏ toàn bộ các tài nguyên (VPC, EC2, VPN, v.v.) đã tạo trong quá trình thực hành để tối ưu chi phí. <br>- Rà soát lại các tiêu chuẩn thiết kế tốt nhất (Best Practices) cho hạ tầng mạng. | 01/05/2026 | 01/05/2026 | [VPC Cleanup](https://000003.awsstudygroup.com/6-cleanup/) |

### Kết quả đạt được tuần 2:
* Hiểu sâu sắc kiến trúc mạng AWS, phân biệt rõ cơ chế hoạt động và phạm vi bảo vệ của Security Groups (Stateful) và NACLs (Stateless).
* Tự tay xây dựng thành công hạ tầng mạng VPC hoàn chỉnh và kiểm soát lưu lượng qua VPC Flow Logs.
* Triển khai và kết nối thành công máy chủ EC2 thông qua Systems Manager Session Manager, giải quyết lỗi định tuyến mạng bằng Reachability Analyzer.
* Thiết lập kết nối AWS Site-to-Site VPN thành công với các VPN Tunnel bảo mật, hiểu cách định tuyến kết nối với Transit Gateway.
* Tiếp cận và áp dụng phương pháp triển khai hạ tầng tự động (IaC) để tối ưu thời gian cấu hình, thực hiện dọn dẹp sạch sẽ tài nguyên tránh phát sinh hóa đơn.
