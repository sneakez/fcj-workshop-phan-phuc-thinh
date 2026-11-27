---
title: "Worklog Tuần 10"
date: 2026-11-16
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---

### Mục tiêu tuần 10:

* Tích hợp luồng webhook/SQS do nhóm đóng góp.
* Hoàn thiện phần CI/CD mà tôi trực tiếp thực hiện với GitHub OIDC.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | Kiểm tra phần xử lý webhook bất đồng bộ và SQS. <br> - Phần phát triển chính do Bình hỗ trợ | 16/11/2026 | 16/11/2026 | [Lịch sử commit NexusOMS](https://github.com/sneakez/nexus-aws/commits/main/) |
| 3 | Tích hợp thay đổi về dữ liệu demo và kiểm tra lại luồng xử lý. | 17/11/2026 | 17/11/2026 | [Kho mã nguồn NexusOMS](https://github.com/sneakez/nexus-aws) |
| 4 | Rà soát tài liệu triển khai và các biến môi trường. | 18/11/2026 | 18/11/2026 | [Tài liệu NexusOMS](https://github.com/sneakez/nexus-aws/tree/main/docs) |
| 5 | Kiểm tra IAM và các bước thực hành trong Workshop. | 19/11/2026 | 19/11/2026 | [Workshop](../../../5-workshop/) |
| 6 | Cấu hình workflow deploy NexusOMS lên AWS bằng GitHub OIDC, tắt CD cũ và cho CI chạy khi workflow thay đổi. | 20/11/2026 | 20/11/2026 | [GitHub OIDC với AWS](https://docs.github.com/en/actions/security-for-github-actions/security-hardening-your-deployments/configuring-openid-connect-in-amazon-web-services) |
| 7 | Kiểm tra lại quy trình GitHub Actions, đề xuất dự án và nội dung báo cáo. | 21/11/2026 | 21/11/2026 | [Kho mã nguồn NexusOMS](https://github.com/sneakez/nexus-aws) |

### Kết quả đạt được tuần 10:

* Cấu hình GitHub Actions dùng OIDC để triển khai lên AWS.
* Kiểm tra và tích hợp phần SQS do Bình hỗ trợ.
* Cập nhật tài liệu triển khai và các bước kiểm tra Workshop.
