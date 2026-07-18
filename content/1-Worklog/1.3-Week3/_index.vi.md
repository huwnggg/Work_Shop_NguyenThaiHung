---
title: "Worklog Tuần 3"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.3. </b> "
---

### Mục tiêu tuần 3:
* Tìm hiểu và khởi tạo môi trường Cloud9 IDE trực tuyến trên AWS Console.
* Thành thạo các thao tác cơ bản trong Cloud9 bao gồm quản lý file, chỉnh sửa code và tích hợp AWS CLI.
* Tìm hiểu cơ chế phân quyền ứng dụng và phân tích rủi ro khi sử dụng các cặp Access Key/Secret Access Key.
* Thực hành giải pháp phân quyền an toàn cho ứng dụng trên máy chủ thông qua EC2 Instance Profile (IAM Role).
* Rà soát tài nguyên và thực hiện dọn dẹp sạch sẽ tài nguyên thực hành (Cleanup) của cả hai bài lab.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| Thứ Hai | **AWS Cloud9 - Khởi tạo & Tính năng cơ bản** <br>- Tìm hiểu và khởi tạo môi trường phát triển tích hợp (IDE) AWS Cloud9 trực tuyến. <br>- Làm quen với giao diện Dashboard, các công cụ quản lý tệp tin và terminal. | 04/05/2026 | 04/05/2026 | [Create Cloud9](https://000049.awsstudygroup.com/1-createcloud9/) <br>[Cloud9 Basic Features](https://000049.awsstudygroup.com/2-basicfeature/) |
| Thứ Ba | **AWS Cloud9 - Tích hợp AWS CLI** <br>- Tìm hiểu và thực hành các lệnh AWS CLI thông qua tích hợp terminal trên Cloud9. <br>- Đọc ghi thông tin tài nguyên AWS trực tiếp qua dòng lệnh. | 05/05/2026 | 05/05/2026 | [Use AWS CLI](https://000049.awsstudygroup.com/3-useawscli/) |
| Thứ Tư | **Phân quyền ứng dụng - Chuẩn bị môi trường** <br>- Khởi tạo máy chủ ảo EC2 và không gian lưu trữ S3 bucket để phục vụ việc cấu hình kiểm tra phân quyền. | 06/05/2026 | 06/05/2026 | [Environment Prep](https://000048.awsstudygroup.com/1-prepare/) |
| Thứ Năm | **Phân quyền ứng dụng - Cấu hình Access Key & Rủi ro bảo mật** <br>- Tạo IAM User, sinh mã Access Key để kiểm tra kết nối từ máy chủ EC2 tới S3. <br>- Nhận diện các rủi ro bảo mật nghiêm trọng khi lưu mã Access Key cứng trên máy chủ. | 07/05/2026 | 07/05/2026 | [Access Key Risk](https://000048.awsstudygroup.com/2-accesskey/) |
| Thứ Sáu | **Cấp quyền an toàn qua IAM Role & Dọn dẹp tài nguyên** <br>- Thiết lập phân quyền an toàn bằng cách tạo IAM Role và gán trực tiếp cho máy chủ EC2 (Instance Profile). <br>- Xác minh kết nối an toàn đến S3. Thực hiện dọn dẹp sạch sẽ tài nguyên ở cả 2 bài lab (Cloud9, EC2, S3, IAM user/role) để tránh phát sinh chi phí. | 08/05/2026 | 08/05/2026 | [IAM Role for EC2](https://000048.awsstudygroup.com/3-iamroleec2/) <br>[Cloud9 Cleanup](https://000049.awsstudygroup.com/4-cleanup/) <br>[IAM Role Cleanup](https://000048.awsstudygroup.com/4-cleanup/) |

### Kết quả đạt được tuần 3:
* Khởi tạo thành công môi trường Cloud9 IDE trực tuyến và thực hành viết code, thao tác command line mượt mà.
* Tận dụng tốt bộ công cụ AWS CLI đã được cấu hình sẵn trên Cloud9 để truy vấn thông tin AWS nhanh chóng.
* Nhận thức rõ các nguy cơ lộ lọt thông tin bảo mật khi hardcode Access Key/Secret Key trên máy chủ ảo.
* Triển khai xuất sắc giải pháp bảo mật nâng cao IAM Role cho máy chủ EC2, giúp ứng dụng tự động truy cập dịch vụ AWS an toàn qua metadata credentials.
* Hoàn thành dọn dẹp và xóa toàn bộ tài nguyên thừa từ cả hai bài thực hành nhằm kiểm soát chi phí tối ưu.
