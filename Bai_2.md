## Bài 2: Chuổi tấn công từ mật khẩu rò rỉ

### 1. Cơ chế Hacker sử dụng mật khẩu bị rò rỉ

- Hacker lấy được mật khẩu từ diễn đàn công nghệ bị hack.
- Vì sử dụng cùng mật khẩu <span>`123456`</span> cho Gmail, Facebook và GitHub nên Hacker thử đăng nhập vào các tài khoản này.
- Nếu mật khẩu giống nhau, Hacker có thể chiếm quyền truy cập nhiều tài khoản.
- Đây gọi là Credential Stuffing, tạo ra hiệu ứng domino khiến nhiều tài khoản bị mất cùng lúc.

### 2. Tại sao mật khẩu cảm tính dễ bị bẻ khóa?

- Mật khẩu như <span>`123456`</span>, ngày sinh hoặc tên cá nhân rất dễ đoán.
- Hacker có thể sử dụng công cụ tự động để thử nhiều mật khẩu phổ biến.
- Mật khẩu do máy tính tạo ra thường dài, ngẫu nhiên và khó đoán hơn.
- Vì vậy, nên sử dụng mật khẩu riêng cho từng tài khoản.

### 3. Tại sao nên sử dụng Password Manager?

- Password Manager giúp lưu trữ mật khẩu tập trung, không cần ghi ra giấy hoặc ghi chú trên điện thoại.
- Có thể sử dụng mã hóa **AES-256** để bảo vệ dữ liệu mật khẩu trong két sắt số.
- **AES-256** sử dụng khóa mã hóa 256 bit, khiến việc giải mã trái phép rất khó nếu không có khóa phù hợp.
- Chỉ cần nhớ một Master Password đủ mạnh để truy cập kho mật khẩu.
- Nên bật xác thực hai yếu tố (2FA) để tăng bảo mật.
