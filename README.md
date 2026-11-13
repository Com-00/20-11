# 🌟 Thiệp 20/11 — ETD Institute

Tấm thiệp điện tử chúc mừng **Ngày Nhà Giáo Việt Nam 20/11** do ETD Institute phát hành.
Thuần **HTML5 + CSS3** — không JavaScript, không framework, không backend.

---

## 📂 Cấu trúc thư mục

```
20-11/
├── index.html   ← Mở file này bằng trình duyệt
├── style.css    ← Toàn bộ thiết kế và animation
├── logo.png     ← Logo ETD Institute (PNG nền trong suốt)
└── README.md    ← File hướng dẫn này
```

---

## 🚀 Cách mở thiệp

1. Nhấn đúp vào `index.html` để mở bằng trình duyệt (Chrome / Edge / Firefox).
2. Chờ 1–2 giây để hiệu ứng khởi động hoàn tất.
3. Nhấn nút **"MỞ THIỆP TRI ÂN"** để bước vào phần chính.

> Kết nối Internet giúp load Google Fonts (Playfair Display, Cormorant Garamond, Montserrat) đẹp hơn.
> Nếu offline, trình duyệt sẽ dùng font serif/sans mặc định — thiệp vẫn hiển thị đúng.

---

## 🖼️ Thay Logo

Logo nằm tại vị trí được đánh dấu rõ trong cả hai file:

**Trong `index.html`** — tìm comment `<!-- PERSONAL LOGO AREA -->`:
```html
<!-- PERSONAL LOGO AREA — Logo container below -->
<div class="logo-container">
  <div class="logo-glow-ring"></div>
  <img src="logo.png" alt="Tên tổ chức của bạn" class="logo-img" />
</div>
```

**Cách thay:**
- Đặt file logo mới (PNG nền trong suốt hoặc SVG) vào cùng thư mục.
- Đổi `src="logo.png"` thành tên file logo mới, ví dụ: `src="my-logo.png"`.
- Cập nhật `alt="..."` thành tên tổ chức/cá nhân của bạn.
- Cập nhật văn bản trong `.logo-name-text` và `.logo-sub-text` nếu cần.

**Kích thước logo khuyến nghị:** 300×300 px trở lên, nền trong suốt (PNG-24 hoặc SVG).

---

## 🎨 Bảng màu chủ đạo

| Màu | Hex | Vai trò |
|-----|-----|---------|
| Midnight Navy | `#0b0f1f` | Nền chính |
| Royal Burgundy | `#3f0d1a` | Điểm nhấn tối |
| Champagne Gold | `#c8993b` | Ánh kim chính |
| Light Gold | `#e8c56a` | Chi tiết sáng |
| Warm Ivory | `#f4efe4` | Text chính |

---

## ✏️ Chỉnh sửa nội dung

| Nội dung | Vị trí trong `index.html` |
|----------|--------------------------|
| Tagline mở màn | `<p class="opening-tagline">` |
| Tiêu đề Scene 2 | `<h2 class="gratitude-title">` |
| Trích dẫn Scene 2 | `<blockquote class="gratitude-quote">` |
| Tiêu đề bài thơ | `<h3 class="poem-title">` |
| Nội dung bài thơ | Các `<div class="stanza">` |
| Lời chúc footer | `<p class="footer-wish">` |

---

## 📱 Responsive

Thiệp tương thích hoàn toàn:
- ✅ Desktop (1920px+)
- ✅ Laptop (1366px)
- ✅ Tablet (768px)
- ✅ Mobile (375px+)
- ✅ Hỗ trợ `prefers-reduced-motion`

---

## 🔧 Yêu cầu kỹ thuật

- Trình duyệt hiện đại: Chrome 90+, Edge 90+, Firefox 90+, Safari 14+
- **Không cần server**, mở trực tiếp từ file là đủ.
- **Không có JavaScript** — 100% HTML5 + CSS3.

---

*ETD Institute · Viện Phát Triển Giáo Dục và Đào Tạo · Ngày Nhà Giáo Việt Nam 20/11*
