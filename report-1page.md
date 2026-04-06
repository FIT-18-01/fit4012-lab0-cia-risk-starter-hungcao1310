# FIT4012 - Report 1 Page
## Lab 01 - CIA & Risk: Hệ thống lưu điểm

### 1. Mục tiêu bài lab
- Nhận diện tài sản cần bảo vệ trong một hệ thống thông tin đơn giản.
- Phân biệt Confidentiality, Integrity, Availability.
- Xác định threat, vulnerability, mitigation.
- Thực hành workflow GitHub cơ bản để nhận và nộp bài.

### 2. Cách làm
- Đọc bối cảnh và xác định các thành phần quan trọng của hệ thống.
- Phân tích từng sự cố theo bộ ba CIA.
- Chọn sự cố B để phân tích sâu hơn theo threat - vulnerability - mitigation.
- Hoàn thiện bài làm trong repo và commit/push lên GitHub.

### 3. Kết quả chính
**Assets:**
- Dữ liệu điểm của sinh viên.
- Thông tin đăng nhập và quyền truy cập của giảng viên/sinh viên.
- Hệ thống ứng dụng quản lý điểm và cơ sở dữ liệu lưu trữ.

**CIA mapping:**
- Sự cố A -> Availability
- Sự cố B -> Integrity
- Sự cố C -> Confidentiality

**Phân tích sự cố B:**
- Threat: Kẻ tấn công nội bộ hoặc người dùng trái phép thay đổi điểm số trong hệ thống.
- Vulnerability: Kiểm soát truy cập và xác thực yếu, cho phép sửa điểm không hợp lệ.
- Mitigation: Áp dụng phân quyền chặt chẽ, kiểm tra xác thực hai yếu tố và ghi nhật ký chỉnh sửa điểm.

### 4. Kết luận ngắn
Bài lab giúp em thấy rõ sự khác biệt giữa Confidentiality, Integrity và Availability trong một hệ thống lưu điểm. Sự cố điểm bị thay đổi là vấn đề nghiêm trọng vì ảnh hưởng trực tiếp đến tính công bằng và niềm tin của sinh viên. Em cần chú ý xác định rõ threat/vulnerability trước khi đề xuất mitigation để giải pháp phù hợp. Hệ thống cần được thiết kế sao cho chỉ người có quyền mới thay đổi dữ liệu quan trọng.
