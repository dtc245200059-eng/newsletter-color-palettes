# [Bài tập] Phối Màu Sắc Cho Newsletter (Trello Edition)

Dự án thực hành kỹ năng phối màu sắc trong thiết kế trải nghiệm người dùng (UX) và giao diện người dùng (UI) bằng công cụ **Adobe Color**, áp dụng trên cấu trúc bản tin điện tử (**Newsletter**) phong cách Trello với **Bootstrap 5** và **CSS Custom Variables**.

---

## 📁 Cấu trúc Dự án

```text
├── index.html                  # Trang Showcase tương tác (Live Switcher, So sánh song song, Bảng mã màu, Hướng dẫn nộp bài)
├── newsletter_version1.html    # Phiên bản 1: Dynamic Tech & Productivity (Trello Blue & Coral)
├── newsletter_version2.html    # Phiên bản 2: Mindful Focus & Organic Elegance (Emerald Pine & Amber)
├── css/
│   ├── style1.css              # Định nghĩa biến CSS Palette 1 & tiện ích
│   └── style2.css              # Định nghĩa biến CSS Palette 2 & tiện ích
└── README.md                   # Báo cáo phân tích lý thuyết màu sắc & hướng dẫn nộp bài
```

---

## 🎨 Phân tích Chi tiết 2 Bộ Màu (Adobe Color)

### 1. Phiên bản 1: **Dynamic Tech & Productivity** (Công nghệ Năng động)

- **Quy tắc bánh xe màu Adobe Color:** **Tương đồng & Bổ túc (Analogous + Complementary Accent)**
- **Mục tiêu UX/UI:** Kế thừa bản sắc nhận diện thương hiệu Trello/Atlassian, truyền tải cảm giác tin cậy, thông minh và tràn đầy năng lượng thúc đẩy hành động.
- **Tỉ lệ vàng phân bổ 60 - 30 - 10:**
  - **60% Nền & Màu chính (Primary):** `#0065FF` (Trello Royal Blue) kết hợp với nền trang `#F4F5F7` và nền thẻ trắng `#FFFFFF`.
  - **30% Màu bổ trợ (Secondary):** `#00B8D9` (Cyan Teal) tạo cảm giác tươi mới, hiện đại và kích thích tính sáng tạo.
  - **10% Màu điểm nhấn (Accent CTA):** `#FF5630` (Coral Red/Orange) – sắc cam san hô đối xứng trên bánh xe màu, có độ bắt mắt cao nhất, dùng riêng cho các nút kêu gọi hành động (Call To Action).
- **Tiêu chuẩn tương phản:** Màu chữ `#172B4D` trên nền `#F4F5F7` đạt tỉ lệ tương phản **12.4:1** (vượt chuẩn **WCAG AAA** tối thiểu 7:1).

| Thành phần UI | Tên màu | Mã HEX | Vai trò trong giao diện |
| :--- | :--- | :--- | :--- |
| **Primary** | Royal Blue | `#0065FF` | Header, Logo, thanh tiến độ, tiêu đề nổi bật |
| **Primary Dark** | Deep Ocean | `#0747A6` | Preheader bar, hiệu ứng hover, viền tương tác |
| **Secondary** | Cyan Teal | `#00B8D9` | Thẻ tính năng Power-Ups, nhãn trạng thái |
| **Accent (CTA)** | Coral Red | `#FF5630` | Nút hành động chính (Khám phá ngay, Tạo bảng) |
| **Background** | Light Slate | `#F4F5F7` | Nền trang dịu mắt, tăng tính thẩm mỹ |
| **Text Main** | Deep Charcoal | `#172B4D` | Tiêu đề và văn bản chính, chống mỏi mắt |

---

### 2. Phiên bản 2: **Mindful Focus & Organic Elegance** (Tập trung Tĩnh tại & Thanh lịch)

- **Quy tắc bánh xe màu Adobe Color:** **Bổ túc bộ ba (Triadic / Split-Complementary)**
- **Mục tiêu UX/UI:** Thay đổi hoàn toàn tâm trạng (mood) của người đọc sang trạng thái cân bằng, tĩnh lặng (Mindfulness & Deep Work), phù hợp với đối tượng làm việc đòi hỏi sự tập trung sâu và giảm tải stress công việc.
- **Tỉ lệ vàng phân bổ 60 - 30 - 10:**
  - **60% Nền & Màu chính (Primary):** `#0E6251` (Deep Emerald/Pine Green) kết hợp với nền trang ngà ấm `#F5F7F6`.
  - **30% Màu bổ trợ (Secondary):** `#1ABC9C` (Jade Mint Green) mang lại sự tái tạo sinh khí và tươi mát.
  - **10% Màu điểm nhấn (Accent CTA):** `#E67E22` (Warm Amber/Vàng hổ phách) – tạo độ ấm áp, quý phái và thu hút ánh nhìn một cách tinh tế.
- **Tiêu chuẩn tương phản:** Màu chữ `#142823` trên nền `#F5F7F6` đạt tỉ lệ tương phản **14.2:1** (đạt chuẩn tối đa **WCAG AAA**).

| Thành phần UI | Tên màu | Mã HEX | Vai trò trong giao diện |
| :--- | :--- | :--- | :--- |
| **Primary** | Deep Pine Green | `#0E6251` | Header, Logo, thương hiệu tập trung |
| **Primary Dark** | Pine Shadow | `#084438` | Preheader bar, viền thẻ đậm, trạng thái hover |
| **Secondary** | Jade Green | `#1ABC9C` | Khối tính năng Sức khỏe & Cân bằng |
| **Accent (CTA)** | Warm Amber | `#E67E22` | Nút hành động chính (Khám phá không gian) |
| **Background** | Calming Off-White | `#F5F7F6` | Nền trang hữu cơ, hạn chế ánh sáng chói |
| **Text Main** | Forest Charcoal | `#142823` | Văn bản chính tương phản cao, rõ ràng |

---

## 🚀 Hướng Dẫn Xem Trực Tiếp & Kiểm Thử

1. Mở file `index.html` trong bất kỳ trình duyệt web nào (Chrome, Edge, Safari, Firefox).
2. Sử dụng thanh công cụ điều khiển:
   - **Tab Trực quan Switcher:** Chuyển đổi giữa 2 phiên bản hoặc đổi giả lập kích thước màn hình (Desktop / Tablet / Mobile).
   - **Tab So sánh song song:** Đặt 2 phiên bản cạnh nhau để cảm nhận sự thay đổi tâm lý người dùng khi tiếp cận màu sắc.
   - **Tab Bảng mã màu & Phân tích:** Nhấp vào bất kỳ thẻ màu nào để sao chép nhanh mã HEX vào bộ nhớ tạm.
   - **Mở từng phiên bản độc lập:** Nhấp vào nút `Mở Phiên bản 1` (`newsletter_version1.html`) hoặc `Mở Phiên bản 2` (`newsletter_version2.html`).

---

## 📤 Hướng Dẫn Nộp Bài (GitHub hoặc CodePen)

### Cách 1: Nộp qua GitHub (Khuyên dùng)

1. Mở cửa sổ Terminal tại thư mục này và chạy các lệnh:
   ```bash
   git init
   git add .
   git commit -m "feat: complete newsletter color palettes assignment with Adobe Color"
   ```
2. Đăng nhập vào [GitHub](https://github.com/), tạo một Repository mới (ví dụ: `newsletter-color-palettes`).
3. Đẩy code lên GitHub:
   ```bash
   git remote add origin https://github.com/<USERNAME>/newsletter-color-palettes.git
   git branch -M main
   git push -u origin main
   ```
4. Kích hoạt **GitHub Pages** (Tùy chọn để có link demo trực tuyến):
   - Vào tab **Settings** của repository -> Chọn mục **Pages**.
   - Tại phần **Branch**, chọn `main` và thư mục `/(root)`, sau đó nhấn **Save**.
   - Sau 1-2 phút, bạn sẽ nhận được đường link dạng: `https://<USERNAME>.github.io/newsletter-color-palettes/`.

### Cách 2: Nộp qua CodePen

1. Truy cập [CodePen.io](https://codepen.io/pen).
2. Mở file `newsletter_version1.html` (hoặc `newsletter_version2.html`):
   - Vào **Settings > CSS** trong CodePen và thêm 2 link CDN:
     - `https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css`
     - `https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css`
   - Sao chép toàn bộ phần trong cặp thẻ `<style> ... </style>` dán vào ô **CSS**.
   - Sao chép toàn bộ nội dung bên trong thẻ `<body> ... </body>` dán vào ô **HTML**.
3. Nhấn **Save** và sao chép đường link Pen để dán vào phần nộp bài.

---

## 📝 Mẫu Văn Bản Dán Vào Phần Nộp Bài

```text
Kính gửi Thầy/Cô, em xin nộp bài tập "Phối màu cho newsletter":
- Link GitHub Repository: [Điền link GitHub của bạn tại đây]
- Link Demo Trực tuyến / CodePen: [Điền link trực tuyến nếu có]

Tóm tắt ý tưởng phối màu từ Adobe Color:
1. Phiên bản 1 (Dynamic Tech & Productivity): Áp dụng quy tắc Tương đồng & Bổ túc (Analogous + Complementary). Màu chủ đạo Royal Blue (#0065FF), kết hợp Cyan Teal (#00B8D9) và điểm nhấn nút CTA Coral Red (#FF5630). Mang lại cảm xúc chuyên nghiệp, hiện đại và kích thích hành động.
2. Phiên bản 2 (Mindful Focus & Organic Elegance): Áp dụng quy tắc Bổ túc bộ ba (Triadic / Split-Complementary). Màu chủ đạo Deep Emerald Green (#0E6251), bổ trợ Jade Green (#1ABC9C) và điểm nhấn Warm Amber (#E67E22). Tạo không gian làm việc tĩnh tại, giảm căng thẳng (Deep Work).
- Cả hai phiên bản đều tuân thủ tỉ lệ màu 60-30-10 và đạt chuẩn tương phản trợ năng WCAG AAA.
```
