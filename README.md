# Build Khắc Chế LMHT

Trang HTML một file, chọn đường, tướng của bạn và tướng đối thủ để nhận gợi ý thứ tự lên đồ, giày, bảng ngọc và cách chơi khắc chế theo patch 26.22.

## Cách chạy

Mở `index.html` bằng trình duyệt. Không cần cài đặt gì.

## Lưu ý

- Gợi ý tính theo luật khắc chế (loại sát thương, khống chế, hồi máu, lá chắn, độ trâu), không phải thống kê tỉ lệ thắng.
- Bộ đồ lõi là bộ mặc định theo kiểu tướng. Một số tướng có bộ riêng trong biến `OVR` của `index.html`.
- Chưa có Zaahen và Locke. Chưa có đồ khởi đầu và phần thưởng nhiệm vụ vị trí.
- Cần đối chiếu tên và giá đồ trong cửa hàng game sau mỗi patch.

## Cập nhật theo patch

Sửa trực tiếp trong `index.html`:

- `R`: danh sách tướng, đường, loại sát thương, kiểu tướng, đặc điểm.
- `ARCH`: bộ đồ, giày, rune mặc định theo kiểu tướng.
- `OVR`: bộ đồ riêng cho từng tướng.
- `PATCH` và `ITEMPATCH`: ghi chú buff, nerf của patch hiện tại.
