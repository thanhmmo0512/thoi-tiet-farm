# Sổ Vườn Chanh Dây (bản demo)

App web quản lý vườn chanh dây, cài được ra màn hình chính điện thoại (iPhone và Android):

- Dashboard sản lượng xuất: hàng Âu, hàng chợ, hàng múc, hàng xô, theo Farm 1-2-3 và mùa vụ.
- Lịch phun thuốc (có thời gian cách ly), bón phân, trồng cây; nhắc việc.
- Thời tiết từ 8 nguồn dự báo qua [Open-Meteo](https://open-meteo.com/) (CC BY 4.0), theo vị trí ghim từng farm hoặc GPS điện thoại; quy tắc báo mưa thử nghiệm, chỉnh được; ghi thời tiết thực tế để kiểm chứng.
- Hỏi nhanh về nhật ký (bộ lọc có sẵn, chưa dùng AI).
- Thùng rác, lịch sử người nhập/sửa/xóa, sao lưu và tải file sao lưu.

**Giới hạn của bản demo:** dữ liệu lưu trên trình duyệt của từng máy, chưa đồng bộ giữa các máy và chưa có đăng nhập (chọn vai trò xem thử ở nút tròn góc trên Trang chủ). Lớp dữ liệu `LocalDB` trong `index.html` dùng cùng kiểu lệnh với Firestore để sau này chuyển sang Firebase.
