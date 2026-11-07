# DI CƯ AN TOÀN – Website có trang quản trị riêng

## Hướng dẫn cài đặt và chạy thử
1. Lưu cả 3 tệp (`index.html`, `admin.html`, `README.md`) chung vào một thư mục trên máy tính.
2. Mở tệp `index.html` bằng trình duyệt web để xem giao diện học viên.
3. Mở tệp `admin.html` bằng trình duyệt web để truy cập khu vực quản trị.
4. Thông tin đăng nhập trang quản trị mẫu: 
   - Tên đăng nhập: `admin`
   - Mật khẩu: `Admin@123`

## Các tính năng quản lý học liệu
- Thêm, sửa, xóa học liệu trực tiếp trên giao diện.
- Phân loại theo cấp độ (1, 2, 3) và loại học liệu (Bài học, Tình huống, Tương tác, Quiz).
- Ẩn hoặc hiển thị học liệu linh hoạt đối với học viên.
- Hỗ trợ nhúng nội dung tương tác (như liên kết Genially, video).

## Giới hạn kỹ thuật của phiên bản chạy thử (Prototype)
- Dữ liệu được lưu trữ trực tiếp trong `localStorage` của trình duyệt đang thao tác.
- Đăng nhập hiện tại mang tính chất demo giao diện, chưa áp dụng cơ chế bảo mật backend thực tế.

## Hướng dẫn nâng cấp chính thức (Production)
Để đưa lên hệ thống thật phục vụ nhiều người dùng, bạn nên tích hợp Backend/Database (như Supabase hoặc Firebase):
- Xây dựng hệ thống xác thực tài khoản phân quyền Admin và Học viên.
- Lưu trữ cơ sở dữ liệu học liệu, lịch sử tiến độ học tập và bài quiz trên Cloud.