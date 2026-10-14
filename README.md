SmartCampus 
Cảnh báo: Dự án hiện đang trong giai đoạn phát triển tích cực, vui lòng không sử dụng cho các mục đích chính thức của nhà trường cho đến khi có thông báo chính thức.

Ứng dụng di động SmartCampus được thiết kế nhằm mang lại trải nghiệm tra cứu thông tin học tập mượt mà và tối ưu nhất cho sinh viên PTIT.

Tính năng đã hoàn thành
Tra cứu lịch học theo mã sinh viên cá nhân và tự động đồng bộ theo tuần học hiện tại.

Xem danh sách phòng trống theo tòa nhà thực tế
:package:Hướng dẫn cài đặt dự án
Để chạy thử dự án ở môi trường nội bộ, bạn sử dụng các lệnh bash sau:

Bash
git clone https://github.com/clb-lap-trinh/smartcampus.git
npm install
npm start
Trạng thái phát triển (Task List)
+ Tra cứu lịch học theo mã sinh viên

+ Xem danh sách phòng trống theo tòa nhà

  Thông báo đẩy (Push Notification)

  Đăng nhập bằng tài khoản cổng thông tin trường

Thư viện sử dụng
Thông tin về các thư viện như sau: Thư viện React Native phiên bản 0.74 dùng để xây giao diện đa nền tảng iOS và Android. Thư viện Axios phiên bản 1.6 dùng để gọi API lấy dữ liệu lịch học.

Ghi chú kỹ thuật
Để hiển thị nguyên văn ký tự đặc biệt trong tài liệu Markdown, chúng ta sử dụng dấu gạch chéo ngược để escape, ví dụ: *thay vì in nghiêng* hoặc #để viết hashtag
