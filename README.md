# Thiệp Cưới Online — Văn Đại & Kim Anh

Chào mừng bạn đến với mã nguồn thiệp cưới trực tuyến cao cấp được thiết kế riêng cho lễ cưới của hai bạn **Nguyễn Văn Đại & Phan Thị Kim Anh**. 

Trang web được xây dựng hoàn toàn bằng **HTML5, CSS3, và JavaScript thuần (Vanilla JS)**, giúp tối ưu hóa tốc độ tải trang cực nhanh trên điện thoại di động và giao diện vô cùng mượt mà.

## 🌟 Các Tính Năng Nổi Bật

1. **Hiệu ứng Mở Thiệp (Envelope Welcome)**: Overlay tinh vân tinh tế che phủ màn hình, mở nhạc nền và bắt đầu tự động cuộn trang (Auto-scroll) nhẹ nhàng khi click "MỞ THIỆP".
2. **Hiệu ứng Cánh Hoa Mai/Đào Rơi (Falling Blossom)**: Hiệu ứng động nhẹ nhàng tạo không khí lãng mạn.
3. **Đồng hồ Đếm Ngược (Countdown Timer)**: Chạy thời gian thực đến thời điểm tổ chức lễ cưới (11:00 ngày 16/09/2026).
4. **Hộp Mừng Cưới Thông Minh (Gift Box / Registry)**:
   - Giao diện thẻ ATM/Tín dụng sang trọng cho cả chú rể và cô dâu.
   - Nút **Sao chép số tài khoản** nhanh và hiển thị thông báo toast.
   - Tích hợp **Mã VietQR động** tự động sinh từ hệ thống VietQR API giúp khách mời quét mã chuyển khoản nhanh không cần nhập số tài khoản.
   - **Tùy biến QR dễ dàng**: Cho phép bạn dễ dàng tự tải lên ảnh mã QR tĩnh của riêng mình để hiển thị trực tiếp.
5. **Thêm Vào Lịch (Add to Calendar)**: Giúp khách mời dễ dàng thêm lịch nhắc nhở vào Google Calendar cá nhân.
6. **Trình Xem Ảnh Lightbox**: Nhấn vào ảnh bất kỳ trong Album để phóng to xem chi tiết.

---

## 📁 Cấu Trúc Thư Mục Dự Án

```text
Wedding/
├── index.html       # File cấu trúc chính (chứa toàn bộ HTML, CSS và JavaScript)
├── README.md        # File hướng dẫn này
└── assets/          # Thư mục chứa tài nguyên hình ảnh (cần tạo và copy ảnh vào đây)
    ├── couple_portrait.png   # Ảnh đại diện cô dâu chú rể
    ├── couple_walking.png    # Ảnh chuyện tình yêu của cặp đôi
    ├── wedding_rings.png     # Ảnh nhẫn cưới / thư viện ảnh
    ├── qr_groom.png          # Mã QR thanh toán của Chú Rể (bạn tải lên ở đây)
    └── qr_bride.png          # Mã QR thanh toán của Cô Dâu (bạn tải lên ở đây)
```

---

## 🚀 Hướng Dẫn Chạy & Xem Thử

1. **Xem trực tiếp**: 
   Bạn chỉ cần kích đúp chuột vào file `index.html` trong thư mục này để mở trực tiếp trên trình duyệt Web (Chrome, Edge, Safari, Firefox).
   
2. **Cơ chế tải ảnh thông minh (Tự động fallback)**:
   - Trang web đã được tích hợp tập lệnh đặc biệt: Nếu không tìm thấy các file ảnh cưới hay mã QR trong thư mục `assets/` cục bộ, nó sẽ **tự động chuyển hướng tải ảnh sang đường dẫn ảnh gốc do AI tạo ra và mã VietQR được tự động tạo từ API**.
   - Nhờ đó, trang web sẽ hiển thị đầy đủ và hoạt động hoàn hảo ngay lập tức khi mở file `index.html` trên máy tính cá nhân của bạn mà không lo bị lỗi ảnh hay thiếu mã QR.

3. **Thay thế hình ảnh & mã QR thực tế của bạn**:
   Khi bạn muốn đóng gói và chia sẻ trang web này lên internet cho bạn bè, hãy tạo một thư mục có tên `assets` nằm cùng cấp với file `index.html`. Sau đó đưa các hình ảnh của bạn vào đó với đúng tên file:
   - `couple_portrait.png` (Ảnh chân dung cưới)
   - `couple_walking.png` (Ảnh đi dạo/album)
   - `wedding_rings.png` (Ảnh nhẫn cưới)
   - `qr_groom.png` (Ảnh mã QR tài khoản chú rể của bạn)
   - `qr_bride.png` (Ảnh mã QR tài khoản cô dâu của bạn)

---

## 🎵 Âm Nhạc Nền

Nhạc nền mặc định được sử dụng là bản cover piano không lời của bài hát nổi tiếng **"Beautiful in White"**. Nhạc được tự động tải từ nguồn internet tốc độ cao, đảm bảo trải nghiệm nghe mượt mà.
