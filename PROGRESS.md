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
