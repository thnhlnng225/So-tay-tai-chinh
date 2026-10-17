# Sổ Tay Tài Chính

## Cài lên điện thoại

Ứng dụng cần được mở từ một địa chỉ HTTPS để trình duyệt cho phép cài PWA và bật chế độ ngoại tuyến. Không mở trực tiếp tệp HTML bằng `file://`.

1. Đưa các tệp trong thư mục này lên một dịch vụ lưu trữ web tĩnh có HTTPS, chẳng hạn GitHub Pages hoặc Netlify.
2. Mở đường dẫn `hethongquanlychitieu.html` trên điện thoại.
3. **Android:** dùng Chrome và nhấn **Cài ứng dụng** trong ứng dụng hoặc chọn **Cài đặt ứng dụng** từ menu trình duyệt.
4. **iPhone:** mở bằng Safari, nhấn **Chia sẻ** rồi chọn **Thêm vào MH chính**.

Service worker lưu giao diện và các tài nguyên đã tải để hỗ trợ mở lại khi ngoại tuyến. Giao dịch tiếp tục được lưu trên thiết bị bằng `localStorage`, không tự đồng bộ giữa các thiết bị; hãy dùng chức năng Xuất để sao lưu dữ liệu.
