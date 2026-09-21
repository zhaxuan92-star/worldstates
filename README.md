# WorldStates

Prototype game mô phỏng quốc gia, tối ưu cho điện thoại.

## Hiện có

- Giao diện dashboard responsive.
- Danh sách quốc gia mẫu.
- Tìm kiếm quốc gia.
- Tổng hợp dân số, GDP và chỉ số hòa bình.
- Tạo quốc gia mới ngay trên trình duyệt.
- Dữ liệu demo lưu bằng `localStorage`, chưa cần backend.
- Có thể chạy trực tiếp bằng GitHub Pages.

## Hướng phát triển

Kiến trúc hiện tại cố ý giữ ở một file HTML để dễ thử nghiệm trên điện thoại. Khi gameplay ổn định có thể tách thành:

1. Frontend.
2. API/backend.
3. Cơ sở dữ liệu quốc gia.
4. Hệ thống Issue/sự kiện.
5. Khu vực và ngoại giao.
6. Tài khoản người chơi.

Đây mới là prototype; dữ liệu hiện tại không đồng bộ giữa các thiết bị.
