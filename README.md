## 1. Vấn đề hiện tại

Hệ thống đặt xe hiện tại của công ty ABC còn tồn tại nhiều hạn chế:

- Việc đặt xe chủ yếu thông qua tổng đài hoặc ứng dụng đơn giản, chưa mang lại trải nghiệm thuận tiện cho khách hàng.
- Việc phân công tài xế chủ yếu được thực hiện thủ công, dẫn đến xử lý chậm và khó mở rộng.
- Khách hàng khó theo dõi trạng thái yêu cầu đặt xe và trạng thái chuyến đi.
- Khách hàng không thể dễ dàng biết tài xế nào đã nhận chuyến và thời gian dự kiến tài xế đến.
- Khi tài xế từ chối hoặc không phản hồi, hệ thống chưa có cơ chế tự động tìm tài xế khác hiệu quả.
- Thông tin thanh toán chưa được quản lý tập trung.
- Khách hàng khó tra cứu lịch sử chuyến đi và thông tin giao dịch.
- Bộ phận vận hành gặp khó khăn trong việc quản lý khách hàng, tài xế, phương tiện và các chuyến đi.
- Hệ thống hiện tại khó mở rộng khi số lượng khách hàng và tài xế tăng lên.
- Việc bổ sung tính năng hoặc tích hợp các dịch vụ mới có thể ảnh hưởng đến các chức năng đang hoạt động.


## 2.Stakeholders

| STT | Stakeholder | Vai trò | Mối quan tâm chính | Mức độ ảnh hưởng |
|---|---|---|---|---|
| 1 | **Ban giám đốc** | Chủ dự án, ra quyết định | Doanh thu, hiệu quả vận hành, khả năng mở rộng, tiến độ 7 tuần | Rất cao |
| 2 | **Khách hàng** | Người sử dụng dịch vụ | Đặt xe, theo dõi chuyến, thanh toán, đánh giá tài xế | Cao |
| 3 | **Tài xế** | Người cung cấp dịch vụ | Nhận chuyến, cập nhật trạng thái, quản lý phương tiện, vị trí | Cao |
| 4 | **Nhân viên vận hành** | Quản lý và hỗ trợ hoạt động | Theo dõi chuyến, quản lý tài xế, xử lý sự cố, tra cứu giao dịch | Cao |
| 5 | **Admin** | Quản trị hệ thống | Quản lý tài khoản, phân quyền, cấu hình, audit log | Cao |
| 6 | **Payment Provider** | Nhà cung cấp thanh toán bên ngoài | Xử lý và trả kết quả giao dịch điện tử | Trung bình - Cao |
| 7 | **Notification Provider** | Nhà cung cấp dịch vụ thông báo | Gửi Push Notification, SMS, Email | Trung bình |
| 8 | **Map/Location Provider** | Nhà cung cấp bản đồ và định vị | Vị trí, khoảng cách, ETA | Trung bình - Cao |


## 3. Stakeholder Matrix

| Stakeholder | Power | Interest | Strategy |
|---|---|---|---|
| **Ban giám đốc** | Cao | Cao | **Manage Closely** – Thường xuyên cập nhật tiến độ, rủi ro và các quyết định quan trọng |
| **Khách hàng** | Thấp | Cao | **Keep Informed** – Thu thập feedback và cập nhật các thay đổi ảnh hưởng đến trải nghiệm |
| **Tài xế** | Thấp | Cao | **Keep Informed** – Thu thập nhu cầu, feedback và đảm bảo quy trình nhận/thực hiện chuyến phù hợp |
| **Nhân viên vận hành** | Cao | Cao | **Manage Closely** – Tham gia phân tích nghiệp vụ, kiểm thử và xác nhận quy trình |
| **Admin** | Cao | Cao | **Manage Closely** – Tham gia xác định yêu cầu quản trị, bảo mật và phân quyền |
| **Payment Provider** | Cao | Trung bình | **Keep Satisfied** – Đảm bảo tích hợp, giao dịch và xử lý lỗi hoạt động ổn định |
| **Notification Provider** | Trung bình | Trung bình | **Monitor** – Theo dõi khả năng tích hợp và trạng thái dịch vụ |
| **Map/Location Provider** | Cao | Trung bình | **Keep Satisfied** – Đảm bảo dữ liệu vị trí, khoảng cách và ETA hoạt động ổn định |
