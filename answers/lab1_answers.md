# Lab 01 Answers
## CIA & Risk: Hệ thống lưu điểm

**Họ và tên:** Hồ Khắc Sơn
**MSSV:** 1871020503
**Lớp/Nhóm:** 18-02

---

## 1. Assets
Liệt kê ít nhất 2 assets cần bảo vệ.

- Asset 1:Dữ liệu điểm sinh viên
- Asset 2:Tài khoản người dùng (giảng viên, sinh viên)

---

## 2. Mapping CIA
Ghép từng sự cố với CIA.

- Sự cố A ->Availability
- Sự cố B ->Integrity
- Sự cố C ->Confidentiality

---

## 3. Phân tích sự cố B
- Threat:Người dùng trái phép hoặc hacker thay đổi dữ liệu điểm
- Vulnerability:Hệ thống phân quyền không chặt chẽ (ai cũng có thể sửa điểm)
- Mitigation:
  +Áp dụng phân quyền rõ ràng – chỉ giảng viên được sửa điểm
  +Ghi log/audit để theo dõi thay đổi
  +Kiểm tra và validate dữ liệu đầu vào
---

## 4. Reflection
Viết 5-7 dòng.
Nếu là quản trị viên hệ thống, em sẽ ưu tiên xử lý sự cố B trước. Đây là vấn đề liên quan đến tính toàn vẹn dữ liệu , ảnh hưởng trực tiếp đến độ chính xác và công bằng trong đánh giá sinh viên. Nếu dữ liệu điểm không đáng tin cậy, hệ thống sẽ mất uy tín nghiêm trọng và có thể gây khiếu nại lớn. Ngoài ra, sự cố này còn có thể là dấu hiệu của lỗ hổng bảo mật nghiêm trọng hoặc bị tấn công. Sau khi đảm bảo dữ liệu được bảo vệ và kiểm soát chặt chẽ, em sẽ xử lý tiếp các vấn đề về sẵn sàng và bảo mật.


---

## 5. Bonus Flag
`FIT4012{A-?-B-?-C-?}`

Flag của em:FIT4012{A-A-B-I-C-C}

