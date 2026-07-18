---
title: "Worklog Tuần 4"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.4. </b> "
---

### Mục tiêu tuần 4:
* Tìm hiểu dịch vụ lưu trữ đối tượng Amazon S3 và giao diện dòng lệnh AWS CLI.
* Thiết lập và phân quyền an toàn cho website tĩnh trên Amazon S3 (Block Public Access, Public Object).
* Kiểm tra website tĩnh và tương tác quản lý qua các câu lệnh AWS CLI.
* Tối ưu hóa hiệu năng phân phối và bảo mật cho website tĩnh thông qua Amazon CloudFront CDN.
* Nghiên cứu các giải pháp S3 nâng cao bao gồm Bucket Versioning, Object Replication và công cụ thay thế hiện đại AWS Amplify.
* Thực hành dọn dẹp sạch sẽ tài nguyên (S3, CloudFront, Cloud9) để tối ưu ngân sách.

### Các công việc cần triển khai trong tuần này:
| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| Thứ Sáu | **Ngày 1: Khởi tạo S3 bucket và Làm quen giao diện AWS CLI** <br>- Tìm hiểu tổng quan về Amazon S3, thực hành tạo S3 bucket. <br>- Sử dụng Cloud9 terminal làm quen và gõ thử các câu lệnh AWS CLI cơ bản. | 08/05/2026 | 08/05/2026 | [Create S3](https://000057.awsstudygroup.com/2-prerequiste/) <br>[Use AWS CLI](https://000049.awsstudygroup.com/3-useawscli/) |
| Thứ Bảy - CN | **Ngày 2: Kích hoạt Host Website tĩnh và Phân quyền S3** <br>- Kích hoạt tính năng Static Website Hosting cho S3 bucket. <br>- Thực hành cấu hình chặn truy cập công khai (Public Access Block) và cấp quyền public read cho đối tượng (Bucket Policy). | 09/05/2026 | 10/05/2026 | [Static Web](https://000057.awsstudygroup.com/3-staticwebsite/) <br>[Block Public Access](https://000057.awsstudygroup.com/4-blockpublicaccess/) <br>[Public Object](https://000057.awsstudygroup.com/5-publicobject/) |
| Thứ Hai | **Ngày 3: Kiểm tra Website và Tương tác qua AWS CLI** <br>- Truy cập đường dẫn endpoint để kiểm tra hoạt động của S3 Static Website. <br>- Sử dụng AWS CLI để thực hành liệt kê tệp tin (s3 ls), xóa hoặc cập nhật tệp tin mà không dùng Console. | 11/05/2026 | 11/05/2026 | [Test Website](https://000057.awsstudygroup.com/6-testwebsite/) <br>[Use AWS CLI](https://000049.awsstudygroup.com/3-useawscli/) |
| Thứ Ba | **Ngày 4: Tăng tốc Website bằng Amazon CloudFront** <br>- Tạo một CloudFront Distribution và cấu hình trỏ nguồn gốc về S3 bucket. <br>- Chặn hoàn toàn truy cập trực tiếp tới S3 để bắt buộc người dùng chỉ truy cập qua HTTPS của CloudFront CDN. | 12/05/2026 | 12/05/2026 | [CloudFront Setup](https://000057.awsstudygroup.com/7-cloudfront/) |
| Thứ Tư | **Ngày 5: Quản lý tính năng S3 nâng cao (Versioning & Replication)** <br>- Thực hành bật Bucket Versioning để quản lý các phiên bản đối tượng. <br>- Thiết lập cơ chế sao chép Cross-Region Replication (CRR) để đồng bộ tệp sang vùng khác tự động. | 13/05/2026 | 13/05/2026 | [Versioning](https://000057.awsstudygroup.com/8-versioning/) <br>[Replication](https://000057.awsstudygroup.com/10-s3ccr/) |
| Thứ Năm | **Ngày 6: Đọc Best Practices và Giải pháp thay thế (AWS Amplify)** <br>- Học tập và nghiên cứu các mẹo tối ưu hóa (Best Practices) cho Amazon S3. <br>- Nghiên cứu AWS Amplify Hosting như một giải pháp thay thế hiện đại giúp tự động CI/CD cho frontend. | 14/05/2026 | 14/05/2026 | [S3 Notes](https://000057.awsstudygroup.com/12-notes/) |
| Thứ Sáu | **Ngày 7: Dọn dẹp tài nguyên (Resource Cleanup)** <br>- Thực hiện xóa bỏ toàn bộ các tài nguyên đã cấu hình (S3 buckets, CloudFront distribution, Cloud9) để hoàn thành an toàn và tối ưu hóa ngân sách. | 15/05/2026 | 15/05/2026 | [Cleanup](https://000057.awsstudygroup.com/11-cleanup/) |

### Kết quả đạt được tuần 4:
* Nắm vững cách khởi tạo và lưu trữ tệp tin đối tượng trong Amazon S3.
* Triển khai thành công S3 Static Website Hosting tích hợp phân quyền bảo mật qua Bucket Policy.
* Tận dụng tối ưu mạng phân phối nội dung Amazon CloudFront CDN để tăng tốc độ tải trang toàn cầu và bảo mật SSL.
* Làm chủ các tính năng lưu trữ dữ liệu cao cấp như Versioning phục vụ khôi phục dữ liệu và Cross-Region Replication để dự phòng thảm họa.
* Tiếp cận và hiểu rõ giải pháp deploy frontend hiện đại AWS Amplify.
* Thực hiện dọn dẹp triệt để hạ tầng S3 & CloudFront sau khi hoàn tất để tránh các phát sinh chi phí ngoài ý muốn.
