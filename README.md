# Nam Định Luxury - Landing Page

Trang web giới thiệu dịch vụ xe ghép chuyên tuyến Nam Định - Hà Nội - Nội Bài.

## ✨ Tính năng nổi bật

### 🎨 Thiết kế
- **Giao diện sang trọng**: Sử dụng bảng màu tinh tế với xanh navy chủ đạo và vàng điểm nhấn
- **Responsive hoàn hảo**: Tương thích mọi thiết bị từ desktop đến mobile
- **Typography đẹp**: Kết hợp font Inter (hiện đại) và Playfair Display (thanh lịch)

### 🎭 Animations & Hiệu ứng
- **Preloader**: Hiệu ứng loading với animation xe hơi
- **Hero Slider**: Slideshow tự động với hiệu ứng Ken Burns
- **Scroll Animations**: Các phần tử xuất hiện mượt mà khi scroll
- **Hover Effects**: Hiệu ứng hover tinh tế trên các elements
- **Parallax**: Hiệu ứng thị sai nhẹ cho hero section

### 📱 Tương tác & UX
- **Floating Action Buttons**: Nút gọi điện và Zalo luôn hiển thị
- **Smooth Scrolling**: Di chuyển mượt mà giữa các sections
- **Back to Top**: Nút quay lại đầu trang
- **Mobile Menu**: Menu hamburger cho mobile
- **Counter Animation**: Số liệu thống kê tăng dần

### 🔗 Call-to-Action
- **Hotline**: 0886 792 222
  - Desktop: Hiển thị số điện thoại
  - Mobile: Tự động mở ứng dụng gọi điện
- **Zalo**: Kết nối trực tiếp đến Zalo chat
- **Đặt chỗ**: Các nút CTA được đặt chiến lược

## 📁 Cấu trúc thư mục

```
Landingpage/
├── index.html              # Trang chính
├── manifest.json           # PWA manifest
├── sw.js                   # Service worker
├── Logo.jpg                # Logo Nam Định Luxury
├── Anh1.jpg - ảnh7.jpg     # Hình ảnh sử dụng
└── assets/
    ├── css/
    │   └── style.css       # Stylesheet chính
    └── js/
        └── script.js       # JavaScript interactions
```

## 🚀 Cách sử dụng

### 1. Chạy website local
```bash
# Sử dụng Python
python -m http.server 8000

# Hoặc sử dụng Node.js
npx serve .

# Hoặc mở trực tiếp index.html trong trình duyệt
```

### 2. Truy cập
Mở trình duyệt và vào: `http://localhost:8000`

### 3. Tùy chỉnh nội dung
- **Thông tin liên hệ**: Sửa số điện thoại trong HTML
- **Hình ảnh**: Thay thế các file ảnh trong thư mục gốc
- **Nội dung**: Chỉnh sửa text trong HTML
- **Màu sắc**: Thay đổi CSS variables trong `:root`

## 📱 Tối ưu Mobile

### Responsive Breakpoints
- **Desktop**: > 1024px
- **Tablet**: 768px - 1024px  
- **Mobile**: < 768px

### Mobile Features
- Touch-friendly buttons (minimum 44px)
- Optimized images for mobile
- Fast loading with service worker
- PWA capabilities

## 🎨 Bảng màu sử dụng

```css
--primary-color: #1a237e      /* Navy blue chủ đạo */
--primary-light: #3949ab      /* Navy blue nhạt */
--secondary-color: #ffd700    /* Vàng điểm nhấn */
--text-primary: #212121       /* Text chính */
--text-secondary: #757575     /* Text phụ */
--background-light: #fafafa   /* Nền sáng */
```

## ⚡ Performance

### Tối ưu hóa
- **Lazy loading** cho hình ảnh
- **Service Worker** cache static assets
- **Minified CSS/JS** trong production
- **Optimized images** với compression

### PWA Features
- Installable trên mobile
- Offline basic functionality
- App-like experience

## 🔧 Customization

### Thay đổi thông tin liên hệ
1. Tìm và thay thế `0886792222` trong HTML
2. Cập nhật link Zalo: `https://zalo.me/[số_điện_thoại]`

### Thêm/thay đổi hình ảnh
1. Thêm ảnh vào thư mục gốc
2. Cập nhật đường dẫn trong HTML
3. Tối ưu ảnh cho web (WebP recommended)

### Tùy chỉnh màu sắc
```css
:root {
    --primary-color: #your-color;
    --secondary-color: #your-accent;
}
```

## 📞 Liên hệ hỗ trợ

- **Hotline**: 0886 792 222
- **Zalo**: 0886 792 222
- **Email**: [Thêm email nếu có]

## 📄 License

© 2025 Nam Định Luxury. All rights reserved.

---
*Được phát triển với ❤️ cho Nam Định Luxury*