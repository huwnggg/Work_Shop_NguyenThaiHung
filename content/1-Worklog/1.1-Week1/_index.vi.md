---
title: "Worklog Tuần 1"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.1. </b> "
---

### Mục tiêu tuần 1:
* Khởi động chương trình học tập, tìm hiểu khái niệm cơ bản về Điện toán đám mây và AWS.
* Thực hành tạo lập tài khoản AWS Free Tier, thiết lập bảo mật cơ bản (MFA) và cấu hình cảnh báo chi phí AWS Budgets.
* Tìm hiểu và phân quyền truy cập nâng cao với IAM User, Group, Policy, và IAM Roles.
* Cấu hình chuyển đổi vai trò (Switch Role), thiết lập thời gian hết hạn phiên (session timeouts) và giám sát qua AWS CloudTrail.
* Rà soát các quy tắc bảo mật IAM và dọn dẹp các tài nguyên thực hành (Cleanup).

### Các công việc cần triển khai trong tuần này:
| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| Thứ Sáu | **KHỞI ĐỘNG & TÌM HIỂU TỔNG QUAN** <br>- Tìm hiểu và làm quen với nền tảng điện toán đám mây AWS. <br>- Gia nhập nhóm chương trình, đọc các tài liệu hướng dẫn và quy định. | 17/04/2026 | 17/04/2026 | Kick-off Materials |
| Thứ Hai | **TẠO TÀI KHOẢN & BẢO MẬT IAM CƠ BẢN** <br>- Thực hành tạo tài khoản AWS Free Tier và thiết lập MFA cho Root. <br>- Tìm hiểu IAM User, Group, Policy và Role. Tạo Admin Group và Admin User để đăng nhập. | 20/04/2026 | 20/04/2026 | [Lab 000001](https://000001.awsstudygroup.com/) <br>[IAM Introduction](https://000002.awsstudygroup.com/1-introduction/) <br>[Create Admin User & Group](https://000002.awsstudygroup.com/2-create-admin-user-and-group/) |
| Thứ Ba | **QUẢN LÝ CHI PHÍ & HỆ THỐNG HỖ TRỢ** <br>- Cấu hình AWS Budgets để thiết lập các cảnh báo chi phí. <br>- Tìm hiểu các gói hỗ trợ kỹ thuật và gửi yêu cầu trên AWS Support. | 21/04/2026 | 21/04/2026 | [Lab 000007](https://000007.awsstudygroup.com/) <br>[Lab 000009](https://000009.awsstudygroup.com/) |
| Thứ Tư | **IAM ROLES & CƠ CHẾ SWITCH ROLES** <br>- Tìm hiểu IAM Roles cấp quyền tạm thời, tạo Admin Role và OperatorUser. <br>- Cấp quyền cho OperatorUser thực hiện chuyển đổi vai trò (Switch role) trên AWS Console. | 22/04/2026 | 22/04/2026 | [AWS Role](https://000002.awsstudygroup.com/3-aws-role/) <br>[Switch Roles](https://000002.awsstudygroup.com/4-switch-roles/) |
| Thứ Năm | **BEST PRACTICES, GIÁM SÁT & DỌN DẸP** <br>- Thiết lập thời gian hết hạn phiên (session timeouts) và giám sát hoạt động qua AWS CloudTrail. <br>- Rà soát phân quyền theo đặc quyền tối thiểu (Least Privilege) và dọn dẹp các tài nguyên IAM đã tạo. | 23/04/2026 | 23/04/2026 | [IAM Best Practices](https://000002.awsstudygroup.com/) <br>[Security Review](https://000002.awsstudygroup.com/) <br>[IAM Cleanup](https://000002.awsstudygroup.com/5-cleanup/) |

### Kết quả đạt được tuần 1:
* Nắm vững kiến thức nền tảng đám mây AWS và cấu hình thành công các cảnh báo chi phí thông qua AWS Budgets.
* Quản trị an toàn tài khoản AWS thông qua IAM Groups, IAM Users và chính sách bảo mật MFA cho tài khoản Root.
* Triển khai thành công cơ chế IAM Roles và chức năng Switch Role trên AWS Management Console để hạn chế gán quyền trực tiếp.
* Thực hành giám sát hoạt động bằng CloudTrail, quản trị thời gian phiên làm việc và rà soát phân quyền an toàn.
* Hoàn thành dọn dẹp sạch sẽ tài nguyên IAM sau khi thực hành xong để tránh các rủi ro bảo mật và chi phí phát sinh.
