# Lab 01 Answers
## CIA & Risk: Hệ thống lưu điểm

**Họ và tên:** CAO MINH HƯNG

**MSSV:** 1871020285

**Lớp/Nhóm:** CNTT 18-01
---

## 1. Assets
Liệt kê ít nhất 2 assets cần bảo vệ.

- Asset 1: Dữ liệu điểm của sinh viên.
- Asset 2: Thông tin đăng nhập và quyền truy cập của giảng viên/sinh viên.
- Asset 3 (nếu có): Hệ thống ứng dụng quản lý điểm và cơ sở dữ liệu lưu trữ.

---

## 2. Mapping CIA
Ghép từng sự cố với CIA.

- Sự cố A -> Availability
- Sự cố B -> Integrity
- Sự cố C -> Confidentiality

---

## 3. Phân tích sự cố B
- Threat: Kẻ tấn công nội bộ hoặc người dùng trái phép thay đổi điểm số trong hệ thống.
- Vulnerability: Kiểm soát truy cập và xác thực yếu, cho phép sửa điểm không hợp lệ.
- Mitigation: Áp dụng phân quyền chặt chẽ, xác thực mạnh và ghi nhật ký chỉnh sửa để phát hiện thay đổi.

---

## 4. Reflection
Nếu là quản trị viên hệ thống, em sẽ ưu tiên xử lý sự cố B trước vì nó ảnh hưởng trực tiếp đến tính chính xác và công bằng của điểm số. Tiếp theo em sẽ xử lý sự cố C để bảo vệ thông tin cá nhân sinh viên. Sự cố A vẫn cần khắc phục để đảm bảo dịch vụ luôn khả dụng, nhưng dữ liệu sai lệch và lộ thông tin là rủi ro nghiêm trọng hơn. Em học được rằng cần phân tích threat, vulnerability và mitigation cùng nhau để chọn biện pháp phù hợp. Quản lý truy cập và kiểm soát quyền là nền tảng quan trọng của an toàn bảo mật.

---

## 5. Bonus Flag
`FIT4012{A-A-B-I-C-C}`

Flag của em: FIT4012{A-A-B-I-C-C}

