# Tiến độ: So sánh với ảnh inspiration (Framer.com)

Ảnh tham chiếu: `C:\Users\Admin\Downloads\www.framer.com__via=godly&dub_id=8cIKP7q0Ee3Y4KiQ.png`
Bản gốc đã sao lưu: `index.backup.html`
Screenshots: `C:\Users\Admin\AppData\Local\Temp\claude\838757565bfd39b2\2896b4d2-8eae-4af8-bd11-41be5fc6770c\scratchpad\shots\`

| # | Khác biệt | Inspiration | Website hiện tại | Trạng thái |
|---|---|---|---|---|
| 1 | Độ rộng nội dung | Cột hẹp (~1040px), lề đen hai bên rất rộng | Container 1280px | ✅ |
| 2 | Bảng màu | Gần như đơn sắc trắng/xám; xanh chỉ ở glow hero | Gradient xanh/tím ở chữ, số, nhãn, link | ✅ |
| 3 | Nút chính | Pill trắng chữ đen, nhỏ gọn | Pill xanh dương, lớn | ✅ |
| 4 | Navbar | Logo + links gom bên trái, phải: text link + nút trắng nhỏ | Links ở giữa, nút xanh | ✅ |
| 5 | Hero: căn lề & chữ | Căn trái, heading trắng ~56px weight 600, sub nhỏ, link phụ bên phải | Căn giữa, 72px weight 800, chữ gradient, có tabs | ✅ |
| 6 | Hero: visual | Khung tối rộng full container, ở giữa là ô input kính phát sáng xanh mạnh | Card mờ, glow yếu, nhãn "Dashboard" | ✅ |
| 7 | Dải logo dưới hero | 2 hàng logo thương hiệu mờ, căn giữa | Dải số liệu gradient có viền trên/dưới | ✅ |
| 8 | Section header | Căn trái, không có nhãn nhỏ, weight 600, nút pill nhỏ bên phải | Nhãn uppercase xanh, weight 800, nhiều header căn giữa | ✅ |
| 9 | Khối dịch vụ | Ảnh sản phẩm lớn + dải 3 cột phân cách bằng đường kẻ mảnh | 6 glass card rời, icon emoji | ✅ |
| 10 | Icon | Icon line mảnh đơn sắc | Emoji màu | ✅ |
| 11 | Feature highlight | Visual lớn phía trên, caption + "Tìm hiểu →" bên dưới, mockup UI xám | Bố cục trái-phải, glow màu, placeholder emoji, nền dot pattern | ✅ |
| 12 | Khối 3D | Thẻ xanh nghiêng phát sáng nằm trong khung tối | Hai khối vuông trôi tự do | ✅ |
| 13 | Bento "full platform" | Lưới bento chia bằng đường kẻ, số lớn 99.99% trong ô, nhãn "Tên →" dưới mỗi ô | 3 dải số liệu lặp lại (social proof, platform cards, stats) | ✅ |
| 14 | Card nhóm giảm giá | Đơn sắc, nhấn nhẹ bằng viền | Badge xanh lá/xanh/tím, chấm xanh | ✅ |
| 15 | Testimonials | Header trái + nút phải, tối giản | Header giữa, sao vàng, avatar gradient, chữ nghiêng | ✅ |
| 16 | Community | Heading trái + 2 nút phải, ảnh chụp marketplace lớn bên dưới | Bố cục trái-phải, glow xanh lá | ✅ |
| 17 | CTA cuối | "Your next idea starts here" + ô nhập kiểu prompt + chip gợi ý | Heading 2 dòng + 2 nút + thanh bar | ✅ |
| 18 | Footer | 6 cột link dày, chữ 13px, tiêu đề cột trắng; hàng dưới: logo + social | 4 cột, tiêu đề uppercase xám, cột brand rộng | ✅ |
| 19 | Khoảng cách section | Rất rộng (~160–200px) | 96–128px | ✅ |
| 20 | Bo góc card | ~12–16px | 16–24px | ✅ |

## Nhật ký
| Bước | Thay đổi | Screenshot |
|---|---|---|
| 0 | Trạng thái ban đầu | `00-before.png` |
| — | Thêm `prefers-reduced-motion` + hook `?static` (để ảnh chụp ổn định, tốt cho a11y) | — |
| 1 | Container 1280 → 1104px | `01-container-view.png` |
| 2 | Bỏ gradient xanh/tím ở chữ, nhãn, link, icon | `02-palette-view.png` |
| 3 | Nút chính trắng/chữ đen, nút phụ xám; min-height 44px | `03-buttons-view.png` |
| 4 | Navbar: logo + links bên trái, nút nhỏ bên phải | `04-navbar-view.png` |
| 5 | Hero căn trái, h1 56px/600, bỏ tabs, thêm link Telegram bên phải | `05-hero-text-view.png` |
| 6 | Hero visual: khung 16:9 + ô prompt kính phát sáng xanh (link Telegram) | `06-hero-visual-view.png` |
| 7 | Dải logo nền tảng + social proof dạng text muted | `07-logos-view.png` |
| 8 | Header căn trái, bỏ nhãn uppercase, thêm nút pill bên phải; FAQ căn trái | `08-headers-view.png` |
| 9 | Mockup "JamesCR Studio" + lưới dịch vụ chia bằng đường kẻ mảnh | `09-services-view.png` |
| 10 | Emoji → icon SVG line | `10-icons-view.png` |
| 11 | Feature: visual lớn trên, caption + link dưới; bảng keyword xám; bỏ dot pattern | `11-features-view.png` |
| 12 | Bỏ khối 3D trôi tự do (tile nghiêng phát sáng nằm trong khung feature) | `12-3d-view.png` |
| 13 | Gộp "đa nền tảng" + 4 card số → lưới bento 5 ô | `13-bento-view.png` |
| 14 | Card nhóm giảm giá đơn sắc, VIP nhấn bằng viền/badge trắng | `14-coupons-view.png` |
| 15 | Testimonials: sao xám, avatar đơn sắc, bỏ chữ nghiêng | `15-testimonials-view.png` |
| 16 | Community: header + 2 nút, ảnh chụp nhóm Telegram lớn | `16-community-view.png` |
| 17 | CTA cuối: ô prompt + chip gợi ý + link gọi điện | `17-cta-view.png` |
| 18 | Footer 5 cột, tiêu đề trắng 13px, hàng logo + social SVG | `18-footer-view.png` |
| 19 | Khoảng cách section 128 → 176px; stats bỏ viền, weight 600 | `19-spacing-view.png` |
| 20 | Bo góc card 16–24 → 12–14px; dọn CSS không còn dùng | `20-radius-view.png` |
| ✓ | Kiểm tra mobile 375px: không tràn ngang, hamburger hoạt động | `21-mobile-view.png` || 21 | Logo 17 → 22px (+30%) ở navbar và footer | `22-font-logo-view.png` |
| 22 | Font Inter → Be Vietnam Pro; line-height tiêu đề 1.08–1.1 → 1.18–1.2 cho dấu chồng | `22-font-logo-view.png` |
| 23 | Hover nút: nhấc 1px + vệt sáng lướt qua + viền/glow nhẹ; bấm thu nhỏ 0.97; chip/link/social cùng hiệu ứng | `23-hover-view.png` |
| 24 | "Liên Hệ Ngay" → Facebook; "Tham gia nhóm/cộng đồng" + "Tham Gia Miễn Phí" → nhóm Zalo; footer: thêm Facebook + Zalo, bỏ TikTok; menu mobile thêm "Liên Hệ Ngay"; stats 500+ → 2,000+ shops đã mở | `24-*.png` |

## Phiên bản 3 — Jamesglobal (2026-11-26)
Bản trước đó được sao lưu: `index.v2-backup.html`

| # | Thay đổi |
|---|---|
| 25 | Đổi thương hiệu JamesCR → Jamesglobal (logo + logo mark gradient, title, meta, toàn bộ nội dung); © 2026 |
| 26 | Dịch vụ: cập nhật "Mở Shop Etsy" (tỷ lệ live cao, bảo hành lâu dài); bỏ "Tối Ưu Listing & SEO" và "Thiết Kế Mockup & Branding"; thêm "Thu Mua USD Payoneer"; lưới 3 + 2 trên desktop |
| 27 | Feature highlight đổi theo dịch vụ mới: các bước mở shop sáng dần khi cuộn tới + widget quy đổi USD Payoneer |
| 28 | Nhóm giảm giá: chỉ còn 1 nhóm cộng đồng (Zalo) — mã sàn TMĐT, đồ điện tử bóc hộp, voucher đồ ăn/uống; viền gradient xoay |
| 29 | Đồng bộ nội dung liên quan: bento, testimonials, community, FAQ, CTA chips, footer |
| 30 | Hiệu ứng: thanh tiến trình cuộn, aurora hero, shimmer tiêu đề, parallax ô prompt, typewriter, marquee logo, reveal blur/scale, stagger, spotlight theo chuột, chấm "live" |
| 31 | Sửa xung đột transition (ô dịch vụ hiện đột ngột, mất delay tiêu đề); kiểm tra mobile 375px không tràn ngang; không lỗi JS |

## Phiên bản 4 — DHDglobal (2026-11-26)
Bản trước được sao lưu: `index.v3-backup.html`

| # | Thay đổi |
|---|---|
| 32 | Đổi thương hiệu → DHDglobal; logo mới: chữ "D" lồng kinh tuyến/xích đạo (globe) trên nền gradient + chữ "DHD" đậm/"global" nhạt; favicon cùng biểu tượng |
| 33 | Payoneer → PingPong (Pipo) ở mọi nơi |
| 34 | Ưu tiên Etsy + PingPong: hero, nút chính, menu, 2 ô dịch vụ "Chủ lực"/"Giá tốt" ở hàng đầu, khối giới thiệu, FAQ, testimonials; nhóm deal lùi xuống thứ yếu |
| 35 | Rải link: FB (29) cho tư vấn/Etsy, Telegram (18) cho báo giá PingPong/hỗ trợ nhanh, Zalo (17) cho nhóm deal, hotline (7); icon MXH trên navbar, thẻ liên hệ ở CTA, nhãn bento thành link, link trong FAQ, footer |
| 36 | Cụm nút liên hệ nổi (desktop) → thanh liên hệ cố định đáy màn hình (mobile); tiêu đề ngắt dòng cân đối |
| 37 | Bỏ chữ "chủ lực"/"thế mạnh" trên giao diện (ưu tiên thể hiện qua bố cục); đánh giá khách hàng rút ngắn 1 câu, giọng tự nhiên — vẫn là nội dung mẫu, cần thay bằng đánh giá thật |
| 38 | Bỏ phần đánh giá khách hàng (mẫu) + dải stats cũ → khối "Nhiệt tình & Tử tế": điểm 4.9/5 với sao tô dần khi cuộn, 2 thẻ giá trị, dải số liệu 2,000+ / 10,000+ / 3+ (số thật có sẵn trong HTML, JS chỉ chạy hiệu ứng đếm) |
| 39 | Section "Kết quả thật từ khách hàng" (#feedback): 11 ảnh Etsy thật, xếp theo doanh thu (79,7K → 4,330 → 3.397 → 874 → 203 US$ → email đơn → Alive → Verified); ảnh gốc PNG không nén, tên khách/tên shop đã làm mờ; lightbox xem ảnh gốc, bấm để zoom 100%, ←/→, vuốt, Esc; thêm "Feedback" vào menu + footer. Ảnh nằm ở `images/feedback/` |
| 40 | Feedback: bỏ toàn bộ chú thích (nhãn trên ảnh, số liệu + mô tả dưới ảnh, "Ngách Etsy · 11 ảnh", ghi chú làm mờ, mô tả section, chữ trong lightbox) — chỉ còn tiêu đề, nút tư vấn và ảnh; lightbox giữ bộ đếm "x / 11" |
| 41 | Feedback Etsy: thêm ảnh Shop Alive (178 sales) làm etsy-08, đánh số lại 09–12; ảnh Verified bỏ ô rộng để lưới 3 cột không hở (12 ảnh). Đang chờ 2 ảnh kháng cáo (Gmail "Khiếu nại thành công" + email reinstated) dạng file |
| 42 | Feedback: thêm tab chuyển nhóm "Dịch vụ Etsy | Thu PingPong"; nhóm PingPong 3 ảnh xếp theo tiền (bảng 8 giao dịch ~12.4K → 3,300 USD → 2,000 USD), che tên + ID khách trong ảnh 3,300 USD; lightbox chỉ lướt trong nhóm đang xem; khối PingPong có link "Xem feedback →" mở thẳng tab PingPong. Đang chờ file: 2 ảnh kháng cáo (Etsy) + 3 ảnh nhóm deal (iPhone, vé ASEAN Cup) |
| 43 | Số liệu: 5,000+ shops Etsy đã mở, 1,000+ shops live thành công, 10,000+ mã giảm giá; bỏ "năm kinh nghiệm" (cả dải số liệu và hàng chữ dưới logo đầu trang) |
| 44 | Feedback Etsy: thêm ảnh "You made a sale" + ảnh Gmail "Khiếu nại thành công" (làm mờ ~20 tên khách); sắp xếp lại 14 ảnh theo nhóm: doanh thu → đơn về → kháng cáo (ô rộng) → Alive → Verified; làm nét toàn bộ ảnh Etsy (unsharp mask nhẹ, giữ PNG gốc kích thước) |
| 45 | Phương châm → "Trách nhiệm, Nhiệt tình & Tử tế": thêm thẻ Trách nhiệm, 3 thẻ dạng icon trái/chữ phải cho gọn |
| 46 | Feedback Etsy: thêm 4 ảnh Etsy chuyển tiền về ngân hàng (€1.216,83 → €1.206,27 → €916,02 → €798,72) ngay sau nhóm doanh thu, làm nét, không chú thích; 18 ảnh, lưới kín trên desktop (3 cột) và tablet (2 cột) |
| 47 | Thêm dịch vụ "Cổng Nhận Tiền Chính Chủ" (hỗ trợ đăng ký/xác minh cổng nhận tiền đứng tên chính khách, phí thấp): menu ngay cạnh "Dịch Vụ Etsy", lưới dịch vụ hàng đầu Etsy → Cổng nhận tiền → PingPong, hero, FAQ, footer; menu desktop bỏ "Liên Hệ" + số điện thoại (đã có nút Liên Hệ Ngay, dock, footer) để không xuống dòng |
| 48 | Feedback: thêm tab "Cổng nhận tiền" (Etsy | Cổng nhận tiền | PingPong), 4 ảnh rút tiền chuyển từ tab Etsy sang (lưới 2×2 lớn) + nút Facebook có icon; menu/ô dịch vụ/footer "Cổng Nhận Tiền" mở thẳng tab này; tab Etsy về 14 ảnh. Không dùng ảnh 30 (bản chưa che của ảnh €1.216,83) |
| 49 | Feedback: thêm tab "Nhóm deal hời" (3 ảnh thật: 4 iPhone nguyên hộp, iPhone xếp chồng, vé chung kết ASEAN Cup 2026) — ảnh dọc, cắt khung đẹp, JPEG 92%; làm mờ hóa đơn VAT và phiếu gửi hàng; nút "Tham gia nhóm Zalo deal hời"; mục Nhóm Deal Hời có link "Xem feedback thành viên →"; thanh tab vuốt ngang trên mobile |
