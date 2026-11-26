---
title: "Worklog Tuần 11"
date: 2026-11-22
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---

### Mục tiêu tuần 11

* Rà soát lại tài liệu triển khai NexusOMS dựa trên bằng chứng từ lần triển khai thực tế.
* Dọn dẹp tài nguyên AWS của môi trường lab và ghi nhận kết quả để tránh phát sinh chi phí ngoài dự kiến.
* Hệ thống hóa kiến thức đã học thành tài liệu có thể tái sử dụng.
* Chuyển các bài học kỹ thuật nổi bật thành nội dung chia sẻ cho cộng đồng.

### Các công việc đã triển khai

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu / minh chứng |
| --- | --- | --- | --- | --- |
| Chủ nhật | - Đối chiếu tài liệu triển khai NexusOMS với các lỗi thực tế đã gặp trên ECS, IAM, ECR, CloudFront, SQS và GitHub Actions. <br> - Phân loại lỗi cần sửa, bước còn thiếu, nội dung chưa được kiểm chứng và điều kiện nghiệm thu workshop. <br> - Chuẩn hóa khuyến nghị về PowerShell, Secrets Manager, OIDC, rollback và cleanup. | 22/11/2026 | 22/11/2026 | Báo cáo rà soát tài liệu triển khai NexusOMS |
| Thứ 2 | - Kiểm kê và dọn dẹp tài nguyên AWS của môi trường demo. <br> - Kiểm tra dependency trước khi xóa ECS, ALB, NAT Gateway, Elastic IP, VPC và các tài nguyên liên quan. <br> - Lưu bằng chứng cleanup và ghi rõ những tài nguyên cần chủ động giữ lại. | 23/11/2026 | 23/11/2026 | Bộ bằng chứng AWS cleanup |
| Thứ 3 | - Xây dựng bộ learning pack từ dự án: bản đồ kiến thức, lộ trình tự làm lại, phản biện tài liệu học gốc và hướng dẫn học code với Gemini. <br> - Viết 5 bài chia sẻ cộng đồng về ECS IAM, GitHub OIDC, S3/CloudFront, NAT Gateway/S3 Endpoint và idempotency. <br> - Chuẩn bị hình minh họa, bản PDF/HTML và từng gói nội dung sẵn sàng đăng. | 24/11/2026 | 24/11/2026 | Bộ learning pack và 5 bài viết AWS |
| Thứ 4 | - Rà soát lần cuối báo cáo thực tập song ngữ, Worklog, Events, Self-evaluation và Sharing & Feedback. <br> - Loại bỏ dữ liệu mẫu, cập nhật thông tin cá nhân, kiểm tra liên kết và cấu hình triển khai Vercel. <br> - Chuẩn bị repository cá nhân để lưu trữ phiên bản nộp cuối cùng. | 25/11/2026 | 25/11/2026 | Repository báo cáo thực tập |

### Kết quả đạt được tuần 11

* Hoàn thành báo cáo rà soát triển khai với danh sách lỗi, bước thiếu và tiêu chí nghiệm thu có thể kiểm chứng.
* Dọn dẹp môi trường AWS lab có kiểm soát và lưu lại bằng chứng phục vụ đối chiếu chi phí.
* Hoàn thiện bộ tài liệu học lại NexusOMS theo hướng từ nền tảng đến quy trình triển khai.
* Hoàn thiện 5 bài chia sẻ kỹ thuật kèm hình minh họa về các bài học quan trọng nhất của dự án.
* Hoàn thiện báo cáo thực tập song ngữ và chuẩn bị bản triển khai công khai trên Vercel.
