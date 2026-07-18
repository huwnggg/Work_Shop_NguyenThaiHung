---
title: "Worklog Tuần 7"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.7. </b> "
---

### Mục tiêu tuần 7:
* Tìm hiểu tổng quan hạ tầng mạng (VPC, Transit Gateway) và hệ thống DNS lai (Route 53 Resolver).
* Chuẩn bị môi trường mạng bao gồm triển khai VPC, tạo Key Pair, chạy CloudFormation Template và cấu hình Security Group.
* Cấu hình Microsoft Active Directory để làm giả lập DNS Server của hệ thống On-premise.
* Cấu hình giải pháp Hybrid DNS giữa AWS và On-premise thông qua Route 53 Resolver Inbound/Outbound Endpoints và Resolver Rules.
* Thiết lập Transit Gateway làm trung tâm hub kết nối Cisco CSR Router và cấu hình VPN Site-to-Site với định tuyến ECMP.
* Cấu hình VPC Peering kết nối các VPC trực tiếp, thiết lập VPC Endpoints qua AWS PrivateLink để bảo mật thông tin.
* Triển khai Transit Gateway Network Manager và Network Insights để theo dõi, khắc phục sự cố mạng tập trung.
* Thực hiện dọn dẹp (Cleanup) sạch sẽ toàn bộ tài nguyên đã tạo ở cả hai bài lab để tránh phát sinh chi phí.

### Các công việc cần triển khai trong tuần này:
| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| Thứ Sáu | **Ngày 1: Tổng quan và Chuẩn bị môi trường (Preparation)** <br>- Tìm hiểu lý thuyết về VPC, Transit Gateway và Route 53 Resolver. <br>- Triển khai VPC, tạo Key Pair, chạy CloudFormation template và Security Group cho cả 2 bài lab. | 29/05/2026 | 29/05/2026 | [Networking Prep](https://000092.awsstudygroup.com/2-prerequiste/) <br>[DNS Prep](https://000010.awsstudygroup.com/2-prerequiste/) |
| Thứ Bảy - CN | **Ngày 2: Phân tích chuyên sâu VPC & Cấu hình máy chủ AD** <br>- Đi sâu vào các thành phần VPC (Subnet, Route Table, IGW, NAT GW). <br>- Kết nối vào Remote Desktop Gateway (RDGW) và triển khai Microsoft Active Directory (AD) giả lập DNS On-premise. | 30/05/2026 | 31/05/2026 | [VPC Deep Dive](https://000092.awsstudygroup.com/3-vpcs/) <br>[RDGW Connection](https://000010.awsstudygroup.com/3-connecttordgw/) <br>[Setup Active Directory](https://000010.awsstudygroup.com/4-setupad/) |
| Thứ Hai | **Ngày 3: Cấu hình Hybrid DNS với Route 53 Resolver** <br>- Thiết lập DNS lai (Hybrid DNS): cấu hình Outbound Endpoints, Inbound Endpoints và Resolver Rules để định tuyến các truy vấn DNS qua lại giữa AWS và On-premise. | 01/06/2026 | 01/06/2026 | [Setup Hybrid DNS](https://000010.awsstudygroup.com/5-setuphyriddns/) |
| Thứ Ba | **Ngày 4: Kết nối đa nền tảng với Transit Gateway & VPN Site-to-Site** <br>- Triển khai Transit Gateway làm thiết bị định tuyến trung tâm (central hub). <br>- Cấu hình kết nối Cisco CSR Router, thiết lập VPN Site-to-Site và cấu hình đường truyền đa luồng ECMP. | 02/06/2026 | 02/06/2026 | [Transit GW & VPN](https://000092.awsstudygroup.com/4-transitgatewayandvpn/) |
| Thứ Tư | **Ngày 5: VPC Peering, Endpoints và Route 53 Internal** <br>- Thực hành liên kết các VPC thông qua VPC Peering. <br>- Cấu hình Route 53 DNS Endpoints, VPC Endpoints cho các dịch vụ AWS qua AWS PrivateLink để bảo mật thông tin nội bộ. | 03/06/2026 | 03/06/2026 | [Route 53 Internal](https://000092.awsstudygroup.com/5-route53/) <br>[VPC Endpoints](https://000092.awsstudygroup.com/6-vpcendpointaws/) <br>[VPC Peering](https://000092.awsstudygroup.com/8-vpcpeering/) |
| Thứ Năm | **Ngày 6: Quản lý mạng tập trung (Transit Gateway Network Manager)** <br>- Triển khai Transit Gateway Network Manager để cấu hình quản trị thiết bị theo site. <br>- Sử dụng công cụ Network Insights để kiểm tra, phân tích đường truyền mạng đã thiết lập. | 04/06/2026 | 04/06/2026 | [Network Manager](https://000092.awsstudygroup.com/9-transitgatewaynetworkmanager/) |
| Thứ Sáu | **Ngày 7: Dọn dẹp hệ thống (Cleanup Resources)** <br>- Thực hiện dọn dẹp, xóa bỏ toàn bộ các tài nguyên đã cấu hình ở cả 2 bài lab (VPC, Transit Gateway, Route 53 Resolver, VPN) để tránh phát sinh chi phí. | 05/06/2026 | 05/06/2026 | [DNS Cleanup](https://000010.awsstudygroup.com/6-cleanup/) <br>[Networking Cleanup](https://000092.awsstudygroup.com/10-cleanup/) |

### Kết quả đạt được tuần 7:
* Nắm vững cấu trúc kết nối mạng lai Hybrid Cloud, quy trình phân giải DNS qua lại giữa AWS và On-premise thông qua Route 53 Resolver.
* Triển khai thành công Microsoft Active Directory trên AWS làm hệ thống giả lập DNS Server cho On-premise.
* Tận dụng tối ưu Transit Gateway làm hub định tuyến trung tâm để kết nối mạng quy mô lớn và cấu hình VPN bảo mật có ECMP tăng băng thông.
* Cấu hình thành công cơ chế kết nối an toàn bảo mật cao (VPC Peering, VPC Endpoints qua AWS PrivateLink).
* Làm chủ công cụ Transit Gateway Network Manager và Network Insights để phát hiện lỗi cấu hình định tuyến và tối ưu hóa hệ thống.
* Hoàn thành dọn dẹp sạch sẽ toàn bộ tài nguyên đã khởi tạo từ cả hai bài thực hành nhằm kiểm soát chi phí.
