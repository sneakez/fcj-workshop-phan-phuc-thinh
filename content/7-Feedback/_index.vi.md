---
title: "Chia sẻ và đóng góp ý kiến"
date: 2026-11-25
weight: 7
chapter: false
pre: " <b> 7. </b> "
---

Phần này tổng hợp trải nghiệm cá nhân và các đề xuất của tôi sau khi tham gia **First Cloud AI Journey** tại văn phòng AWS.

### Trải nghiệm học tập

Điểm có giá trị nhất của chương trình là môi trường khuyến khích học viên tự nghiên cứu và chịu trách nhiệm với kết quả. Tôi không chỉ làm theo hướng dẫn mà phải đọc tài liệu, kiểm tra trạng thái thực tế, giải thích vì sao một cấu hình hoạt động hoặc thất bại và tự hoàn thiện sản phẩm cá nhân.

NexusOMS giúp tôi nhìn thấy mối liên hệ giữa code và hạ tầng. Một thay đổi nhỏ ở Docker image, IAM policy, connection string hoặc CloudFront behavior đều có thể ảnh hưởng đến toàn bộ luồng. Việc phải triển khai, quan sát, sửa lỗi, rollback và cleanup khiến kiến thức về ECS Fargate, ECR, S3, CloudFront, SQS, CloudWatch, CloudTrail, Secrets Manager và GitHub OIDC trở nên cụ thể hơn nhiều so với khi chỉ đọc lý thuyết.

### Sự hỗ trợ và cộng đồng

Các admin và thành viên cộng đồng đã cho tôi thêm góc nhìn khi gặp vấn đề khó. Cách hỗ trợ hiệu quả nhất là gợi ý hướng kiểm tra hoặc đặt câu hỏi phản biện, để tôi tự tìm ra nguyên nhân và ghi lại bài học. Hai sự kiện đã tham gia giúp tôi hiểu rõ hơn tư duy phát triển sản phẩm, xu hướng Cloud & AI, mức độ sẵn sàng của dữ liệu và yêu cầu vận hành hệ thống thực tế.

### Điều tôi hài lòng nhất

- Được tự chọn bài toán NexusOMS và phát triển nó qua nhiều vòng từ nghiệp vụ đến hạ tầng.
- Được trải nghiệm một quy trình gần với thực tế: test, container, CI/CD, deploy, quan sát, xử lý lỗi và cleanup.
- Có đủ bằng chứng để nhìn lại phần nào đã làm được, phần nào mới là thiết kế mục tiêu và phần nào cần học tiếp.
- Chuyển kinh nghiệm cá nhân thành workshop song ngữ, learning pack và các bài viết có thể chia sẻ lại.

### Khó khăn ghi nhận

- Một số lab, repository và ảnh hướng dẫn không còn khớp với giao diện hoặc hành vi hiện tại của dịch vụ.
- Nhiều lỗi triển khai xuất hiện ở ranh giới giữa các dịch vụ nên khó tìm nguyên nhân nếu không có checkpoint rõ ràng.
- Chi phí cloud, secret, quyền IAM và thứ tự cleanup dễ bị xem nhẹ khi người học tập trung vào mục tiêu “chạy được”.
- Các mốc review chưa cố định khiến việc chuẩn bị nội dung và phân bổ thời gian đôi lúc bị dồn vào cuối kỳ.

### Đề xuất cải thiện

- Phiên bản hóa lab theo ngày kiểm chứng, repository/tag/commit và Region đã sử dụng.
- Mỗi chặng nên có checkpoint có thể quan sát: lệnh kiểm tra, trạng thái mong đợi, log cần xem và cách rollback.
- Cung cấp checklist bắt buộc cho secret handling, ngân sách/cost alert và cleanup ngay từ đầu chương trình.
- Thiết lập mốc review định kỳ ngắn để học viên trình bày tiến độ, giới hạn và rủi ro thay vì chờ đến bản cuối.
- Khuyến khích học viên viết lại bài học bằng ngôn ngữ của mình và công khai phần chưa kiểm chứng.

### Định hướng tiếp theo

Tôi sẽ tiếp tục củng cố .NET, PostgreSQL, automated testing và AWS Security; xây dựng lại một phiên bản NexusOMS nhỏ hơn nhưng có tiêu chí production rõ ràng; đồng thời duy trì việc viết bài và tham gia cộng đồng để kiểm tra mức độ hiểu của chính mình.

### Kết luận

First Cloud AI Journey giúp tôi chuyển từ tư duy “làm xong một lab” sang tư duy “chứng minh một hệ thống hoạt động đúng trong phạm vi đã nêu”. Sự chủ động, khả năng đọc bằng chứng và thói quen ghi rõ giới hạn là những giá trị tôi muốn tiếp tục giữ sau chương trình.
