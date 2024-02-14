# Online exam tutorial

Hệ thống hỗ trợ ba loại người dùng: Quản trị viên (Admin), Giảng viên, và Sinh viên. Mỗi loại tài khoản có những chức năng riêng biệt nhằm phục vụ nhu cầu quản lý và học tập.

- Sinh viên, giảng viên sẽ được cấp tài khoản qua bên trường cấp mà cụ thể là do admin tạo tài khoản.
-	 Giảng viên sẽ tạo bài kiểm tra cho một bài kiểm tra và có mật khẩu của bài đó. Sinh viên sẽ được giảng viên gửi mật khẩu cho trước giờ làm bài để vào làm bài thi.
-	Sinh viên sau khi đăng nhập, chọn bài kiểm tra sẽ hiển thị ra tất cả bài kiểm tra chưa làm.
-	 Khi vào làm bài thì sẽ mở ra toàn màn hình và sẽ chặn được tất cả các phím trên bàn phím nóng (hotkey) như Alt F4, ESC, Alt + tab, F5, F11 hay các phím có thể chuyển trang khác trên bàn phím.


## Trang Đăng Nhập

- **Mô Tả:** Trang yêu cầu đăng nhập để truy cập hệ thống, phân biệt ba loại tài khoản: Admin, Giảng viên, và Sinh viên.
- **Cách Sử Dụng:** Nhập thông tin đăng nhập bao gồm tên đăng nhập và mật khẩu.

![image](https://github.com/DinhManhAVG/OnlineExam/assets/112262009/2b80dcaa-9dd5-4da8-a352-2174785869be)

## Quản Trị Viên

### Trang Chính

- **Chức Năng:** 
  - Tạo khóa học mới.
  - Phân quyền và cung cấp tài khoản cho giảng viên và sinh viên.

![image](https://github.com/DinhManhAVG/OnlineExam/assets/112262009/03fdfaf8-68d4-439a-add8-c63ff37a73c5)

### Tạo Tài Khoản Mới

- **Chức Năng:** Thiết lập tài khoản mới cho giảng viên và sinh viên.

![image](https://github.com/DinhManhAVG/OnlineExam/assets/112262009/44579527-0c3c-460f-9fd8-dc0f4e8e166f)

### Tạo Môn Học Mới

- **Chức Năng:** Thêm thông tin về môn học mới bao gồm mã môn học và tên môn học.

![image](https://github.com/DinhManhAVG/OnlineExam/assets/112262009/591aa825-d10f-4352-8ba1-38576b106899)

## Giảng Viên

### Trang Chính

- **Chức Năng:** 
  - Tạo câu hỏi mới cho môn học.
  - Tạo bài kiểm tra mới.

![image](https://github.com/DinhManhAVG/OnlineExam/assets/112262009/a2eb8bbc-872a-4039-a9a0-d4626350efb7)

### Tạo Câu Hỏi Mới

- **Chức Năng:** Nhập câu hỏi và đáp án, chọn loại câu hỏi (một đáp án hoặc nhiều đáp án).

![image](https://github.com/DinhManhAVG/OnlineExam/assets/112262009/ceeb7415-f407-4bdd-906d-a3a0703ed2d5)
![image](https://github.com/DinhManhAVG/OnlineExam/assets/112262009/79c1b6b9-03cc-4b03-9829-68c6a0c984df)

### Tạo Bài Kiểm Tra Mới

- **Chức Năng:** Chọn môn học và nhập thông tin bài kiểm tra bao gồm tên, số lượng câu hỏi, mật khẩu, thời lượng và thời gian bắt đầu.

![image](https://github.com/DinhManhAVG/OnlineExam/assets/112262009/0e922ce6-2e7d-4e98-9833-db3093b25b9d)

### Xem Bài Kiểm Tra Đã Tạo

- **Chức Năng:** Xem danh sách bài kiểm tra đã tạo và thông tin chi tiết.

![image](https://github.com/DinhManhAVG/OnlineExam/assets/112262009/870648db-2ba7-4e1e-91fe-4c8a53bf271f)
![image](https://github.com/DinhManhAVG/OnlineExam/assets/112262009/d0ad586e-d317-47b7-a33f-4a0078648261)

## Sinh Viên

### Trang Chính

- **Chức Năng:** 
  - Xem danh sách bài kiểm tra chưa làm.
  - Xem lịch sử bài kiểm tra đã làm.
![image](https://github.com/DinhManhAVG/OnlineExam/assets/112262009/162b25f8-9d0e-4202-a23a-f247734c6e5e)
![image](https://github.com/DinhManhAVG/OnlineExam/assets/112262009/6cb15b97-7342-4a3d-8de7-b378ccc7c539)
![image](https://github.com/DinhManhAVG/OnlineExam/assets/112262009/4c738593-45f1-4330-abd3-36ed770181c9)

### Tham Gia Bài Kiểm Tra

- **Chức Năng:** Nhập mật khẩu bài kiểm tra và tham gia làm bài.
- Trang làm bài sẽ fullcreen, nhằm mục đích tránh sinh viên làm những việc riêng khi đang trong quá trình làm bài và sẽ chặn được tất cả các phím trên bàn phím nóng (hotkey) như Alt F4, ESC, Alt + tab, F5, F11 hay các phím có thể chuyển trang khác trên bàn phím, trang này chứa thông tin của bài kiểm tra, chứa những câu hỏi (bao gồm cả câu hỏi có 1 đáp án và câu hỏi có nhiều đáp án) và có một đồng hồ đếm ngược khi đang làm bài. Khi chọn phương án trả lời thì phương án được chọn sẽ có màu đậm hơn, và nếu bỏ chọn thì màu sẽ về như ban đầu, những phương án nào được chọn thì sẽ được lưu lại nhằm mục đích nếu có sự cố xảy ra thì sinh viên vẫn có thể giữ được các đáp án đã chọn mà không phải chọn lại từ đầu. Đồng hồ đếm ngược cũng tương tự nếu có sự cố xảy ra thì thời gian vẫn tiếp tục trừ và khi thời gian kết thúc sẽ tự động nộp bài. Khi nộp bài thì đáp án sẽ được xử lý, tính toán để trả về số câu đúng và số điểm
![image](https://github.com/DinhManhAVG/OnlineExam/assets/112262009/543b28ea-db21-42ba-b679-6c593f4c7fc7)
![image](https://github.com/DinhManhAVG/OnlineExam/assets/112262009/0184cf8f-33d6-4223-b2d1-f0cb2e9d4990)

### Xem Kết Quả Bài Kiểm Tra

- **Chức Năng:** Xem điểm số và phản hồi sau khi nộp bài.
![image](https://github.com/DinhManhAVG/OnlineExam/assets/112262009/767524d8-68b7-410a-95cb-c615e3e2f9d0)

### Lịch Sử Bài Kiểm Tra

- **Chức Năng:** Lọc và xem lịch sử bài kiểm tra theo môn học.
![image](https://github.com/DinhManhAVG/OnlineExam/assets/112262009/b5c42a74-2aa4-4d44-9bfc-56b2bce854b3)

