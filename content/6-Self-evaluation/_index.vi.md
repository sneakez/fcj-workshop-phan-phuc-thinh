---
title: "Tự đánh giá"
date: 2026-11-25
weight: 6
chapter: false
pre: " <b> 6. </b> "
---

Trong chương trình **First Cloud AI Journey**, tôi lựa chọn phát triển NexusOMS như một bài toán xuyên suốt thay vì chỉ hoàn thành từng lab riêng lẻ. Quá trình này giúp tôi kết nối kiến thức Kỹ thuật phần mềm với AWS: từ phân tích nghiệp vụ, thiết kế dữ liệu, phát triển giao diện và API đến kiểm thử, đóng gói container, triển khai, quan sát hệ thống và kiểm soát chi phí.

Phần khó nhất không nằm ở việc tạo từng tài nguyên, mà ở việc làm cho toàn bộ luồng hoạt động có thể kiểm chứng. Tôi đã phải đọc log, đối chiếu trạng thái ECS và ALB, kiểm tra quyền IAM, xử lý secret, sửa pipeline GitHub Actions/OIDC, xác minh idempotency của webhook/SQS và dọn dẹp tài nguyên theo đúng thứ tự dependency. Cuối chương trình, tôi tiếp tục rà soát lại tài liệu triển khai, xây dựng learning pack và chuyển các bài học thành nội dung chia sẻ cộng đồng.

### Kết quả tự đánh giá

| STT | Tiêu chí | Minh chứng tự đánh giá | Tốt | Khá | Trung bình |
| --- | --- | --- | --- | --- | --- |
| 1 | **Kiến thức và kỹ năng chuyên môn** | Kết nối React/Vite, .NET, PostgreSQL, Docker và nhiều dịch vụ AWS trong cùng một luồng nghiệp vụ | ☐ | ✅ | ☐ |
| 2 | **Khả năng học hỏi** | Chủ động đọc tài liệu chính thức, thực hành, ghi nhận lỗi và cập nhật cách làm | ✅ | ☐ | ☐ |
| 3 | **Tính chủ động** | Tự đặt giả thuyết, đọc log và thử nghiệm trước khi nhờ hỗ trợ | ✅ | ☐ | ☐ |
| 4 | **Tinh thần trách nhiệm** | Theo dõi công việc đến bước kiểm chứng, lưu bằng chứng và cleanup tài nguyên | ✅ | ☐ | ☐ |
| 5 | **Kỷ luật** | Duy trì tiến độ 11 tuần nhưng vẫn có giai đoạn phải sửa nhiều vòng do chia việc chưa đủ nhỏ | ☐ | ✅ | ☐ |
| 6 | **Tính cầu tiến** | Tiếp nhận phản biện và sửa lại code, kiến trúc, tài liệu cùng cách trình bày | ✅ | ☐ | ☐ |
| 7 | **Giao tiếp** | Mô tả lỗi bằng log, trạng thái tài nguyên và kết quả kiểm tra thay vì chỉ nêu hiện tượng | ☐ | ✅ | ☐ |
| 8 | **Hợp tác** | Trao đổi với admin, thành viên cộng đồng và sử dụng feedback để tiếp tục điều tra | ☐ | ✅ | ☐ |
| 9 | **Ứng xử chuyên nghiệp** | Tôn trọng quy trình, bảo vệ thông tin bí mật và phân biệt rõ phần đã kiểm chứng/chưa kiểm chứng | ✅ | ☐ | ☐ |
| 10 | **Giải quyết vấn đề** | Phân tích lỗi xuyên suốt ứng dụng, CI/CD và hạ tầng thay vì xử lý từng triệu chứng rời rạc | ✅ | ☐ | ☐ |
| 11 | **Đóng góp dự án** | Hoàn thiện demo NexusOMS, workshop song ngữ, learning pack và 5 bài chia sẻ kỹ thuật | ✅ | ☐ | ☐ |
| 12 | **Đánh giá tổng thể** | Đạt mục tiêu học tập và tạo được sản phẩm, tài liệu cùng bằng chứng có thể trình bày | ✅ | ☐ | ☐ |

### Điểm mạnh

- Kiên trì điều tra lỗi bằng bằng chứng và theo dõi vấn đề qua nhiều lớp của hệ thống.
- Có khả năng hệ thống hóa một lượng lớn công việc thành checklist, tài liệu và luồng demo rõ ràng.
- Chú ý đến tính đúng đắn của nghiệp vụ, bảo mật thông tin, khả năng rollback và chi phí sau triển khai.

### Điểm cần cải thiện

- Chia nhỏ phạm vi và đặt tiêu chí hoàn thành sớm hơn để giảm số vòng chỉnh sửa cuối kỳ.
- Củng cố nền tảng .NET, PostgreSQL và testing để giảm phụ thuộc vào quá trình thử-sai.
- Tiếp tục học sâu AWS Security, observability, kiến trúc đa AZ thực sự và tối ưu chi phí production.
- Trình bày vấn đề kỹ thuật ngắn gọn hơn, ưu tiên bối cảnh, bằng chứng, nguyên nhân và quyết định.

### Kết luận

Tôi chưa xem NexusOMS là một sản phẩm production hoàn chỉnh, nhưng dự án đã giúp tôi hình thành tư duy triển khai có kiểm chứng: hiểu phạm vi, đo kết quả, ghi lại giới hạn và dọn dẹp sau thử nghiệm. Đây là tiến bộ quan trọng nhất của tôi sau chương trình và cũng là nền tảng cho giai đoạn học tập tiếp theo.
