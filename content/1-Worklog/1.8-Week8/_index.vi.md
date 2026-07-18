---
title: "Worklog Tuần 8"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.8. </b> "
---

### Mục tiêu tuần 8:
* Tìm hiểu dịch vụ phân phối mạng nội dung toàn cầu Amazon CloudFront CDN và các giải pháp tích hợp S3/EC2 làm nguồn gốc (Origin).
* Cấu hình dự phòng máy chủ với Origin Group (failover) và thiết lập các hành vi lưu trữ bộ đệm (Cache Behavior).
* Thiết lập Response Headers, vô hiệu hóa cache Edge Server (Invalidations) và Custom Error Pages.
* Tìm hiểu điện toán biên Edge Computing, cấu hình và triển khai hàm Lambda@Edge trên CloudFront.
* Giám sát hiệu năng hệ thống CloudFront thông qua Metrics & Logs, phân tích truy vấn qua S3/Athena.
* Thực hiện dọn dẹp sạch sẽ tài nguyên (Tear down) ở cả hai bài thực hành để tối ưu chi phí.

### Các công việc cần triển khai trong tuần này:
| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| Thứ Sáu | **Ngày 1: Tổng quan CloudFront và Tích hợp S3 làm Origin** <br>- Tìm hiểu lý thuyết về mạng CDN của Amazon CloudFront. <br>- Tạo S3 bucket, tải tệp tin index.html và cấu hình CloudFront CDN sử dụng S3 làm Origin. | 05/06/2026 | 05/06/2026 | [CloudFront Intro](https://000130.awsstudygroup.com/1-introduction/) <br>[S3 Bucket Creation](https://000094.awsstudygroup.com/1.1-t%E1%BA%A1o-nh%C3%B3m-s3/) <br>[Upload & Configure CDN](https://000094.awsstudygroup.com/1.2-t%E1%BA%A3i-l%C3%AAn-t%E1%BB%87p-index.html/) & [Configure CDN](https://000094.awsstudygroup.com/1.3-c%E1%BA%A5u-h%C3%ACnh-amazon-cloudfront/) |
| Thứ Bảy - CN | **Ngày 2: Tích hợp EC2 Origin và Thiết lập dự phòng (Origin Group)** <br>- Tạo máy chủ EC2, cấu hình EC2 làm một Origin thứ hai cho CloudFront. <br>- Thiết lập cấu hình Origin Group để tự động chuyển hướng failover giữa nhiều Origin khi có sự cố. | 06/06/2026 | 07/06/2026 | [EC2 & Origin Setup](https://000130.awsstudygroup.com/2--preparation/2.1-createec2/) & [Add EC2 Origin](https://000130.awsstudygroup.com/3-create-cloudfront-distribution/3.1-addec2/) <br>[Origin Group Tutorial](https://000130.awsstudygroup.com/6-origin-group/) |
| Thứ Hai | **Ngày 3: Quản lý Bộ nhớ đệm (Cache Behavior) và Trang lỗi tùy chỉnh** <br>- Tạo và quản lý các hành vi bộ nhớ đệm (Cache Behavior) để tối ưu việc lưu cache. <br>- Cấu hình Custom Error Page hiển thị thông báo lỗi thân thiện với người dùng. | 08/06/2026 | 08/06/2026 | [Cache Behavior](https://000130.awsstudygroup.com/8--cache-behavior/) <br>[Custom Error Page](https://000130.awsstudygroup.com/5-custom-error-page/) |
| Thứ Ba | **Ngày 4: Xóa Cache (Invalidations) và Cấu hình Response Headers** <br>- Thiết lập cấu hình HTTP Response Headers của CloudFront. <br>- Thực hành xóa cache tức thì (Invalidations) trên Edge Server khi cập nhật mã nguồn mới. | 09/06/2026 | 09/06/2026 | [Response Headers](https://000130.awsstudygroup.com/7-response-headers/) <br>[Invalidations](https://000130.awsstudygroup.com/4-distribution-invalidations/) |
| Thứ Tư | **Ngày 5: Tính toán tại biên (Edge Computing) - Khởi tạo Lambda@Edge** <br>- Tiếp cận công nghệ Edge Computing: viết và khởi tạo hàm Lambda@Edge để xử lý logic request/response ngay tại Edge Server nhằm tối ưu hiệu năng. | 10/06/2026 | 10/06/2026 | [Lambda@Edge Init](https://000130.awsstudygroup.com/9-lambda@edge-function/) |
| Thứ Năm | **Ngày 6: Triển khai Lambda@Edge và Giám sát hệ thống (Metrics & Logs)** <br>- Tiến hành deploy hàm Lambda@Edge lên CloudFront Distribution. <br>- Cấu hình giám sát (Metrics & Logs) và tìm hiểu lưu trữ logs về S3, phân tích qua Athena. | 11/06/2026 | 11/06/2026 | [Deploy Lambda@Edge](https://000130.awsstudygroup.com/10-deploy-lambda@edge-function/) <br>[Metrics & Logs](https://000130.awsstudygroup.com/11-metrics-and-logs/) |
| Thứ Sáu | **Ngày 7: Dọn dẹp tài nguyên (Tear down)** <br>- Thực hiện vô hiệu hóa và xóa toàn bộ các tài nguyên thử nghiệm (CloudFront Distribution, S3 buckets, EC2, Lambda@Edge) để tránh phát sinh chi phí. | 12/06/2026 | 12/06/2026 | [Teardown WS1](https://000130.awsstudygroup.com/12-cleanup/) <br>[Teardown WS2](https://000094.awsstudygroup.com/1.4-d%E1%BB%8Dn-d%E1%BA%B9p-t%C3%A0i-nguy%C3%AAn/) |

### Kết quả đạt được tuần 8:
* Nắm vững cơ chế hoạt động mạng phân phối nội dung CDN của Amazon CloudFront, deploy thành công web tĩnh S3 tích hợp CDN.
* Cấu hình thành công Origin Group để tự động failover giữa S3 và EC2, đảm bảo tính sẵn sàng cao (High Availability).
* Làm chủ các tính năng quản lý bộ nhớ đệm (Cache Behavior, Invalidation) và cấu hình Header HTTP linh hoạt.
* Tiếp cận và viết code xử lý logic request/response biên thành công bằng dịch vụ Lambda@Edge.
* Thiết lập hệ thống giám sát CloudFront sử dụng Metrics/Logs và phân tích logs qua Athena.
* Hoàn thành dọn dẹp sạch sẽ 100% tài nguyên thử nghiệm đã khởi tạo để tránh hóa đơn AWS.
