# CLAUDE.md — JamesCR Website

## 🎯 Tổng Quan Dự Án

Website giới thiệu thương hiệu **JamesCR** — cung cấp dịch vụ Etsy (mở shop, tối ưu listing, SEO Etsy, quản lý shop) và các nhóm săn mã giảm giá (coupon groups). Website được xây dựng với phong cách **tối giản, hiện đại, chuyên nghiệp**, lấy cảm hứng từ thiết kế dark premium của Framer.com.

---

## 🏢 Thông Tin Công Ty / Thương Hiệu

| Thông tin | Chi tiết |
|---|---|
| **Tên thương hiệu** | JamesCR |
| **Người điều hành** | Nguyễn Hữu Duy |
| **Lĩnh vực hoạt động** | Dịch vụ bán hàng trên Etsy, Hội mã giảm giá sàn TMĐT |
| **Số điện thoại** | 0877.569.869 |
| **Telegram** | [@jamescr123](https://t.me/jamescr123) |

### Dịch vụ chính
1. **Dịch vụ Etsy** — Mở shop, tối ưu listing, SEO, quản lý & vận hành shop Etsy, thiết kế mockup, xử lý vi phạm & kháng cáo
2. **Hội mã giảm giá sàn TMĐT** — Nhóm săn mã giảm giá trên các sàn thương mại điện tử (Shopee, Lazada, Tiki, TikTok Shop, v.v.)

### Liên hệ hiển thị trên website
- Hotline: `0877.569.869` (hiển thị ở Navbar, Footer, CTA section)
- Telegram: `@jamescr123` (link trực tiếp đến https://t.me/jamescr123)
- Các nút CTA chính nên link đến Telegram hoặc gọi điện (`tel:0877569869`)

---

## 🛠 Tech Stack

- **Framework**: Next.js 14+ (App Router)
- **Styling**: Tailwind CSS v4
- **Animations**: Framer Motion
- **Language**: TypeScript
- **Font**: Inter (Google Fonts) hoặc Geist Sans
- **Icons**: Lucide React
- **Deployment**: Vercel

---

## 🎨 Design System

### Triết lý thiết kế
- **Dark-first**: Nền đen/tối làm chủ đạo, nội dung nổi bật trên nền tối
- **Spacious**: Khoảng cách lớn giữa các section (py-24 đến py-32), tạo cảm giác thở
- **Glow effects**: Hiệu ứng phát sáng xanh dương/tím nhẹ trên các phần tử nổi bật (cards, buttons, hero elements)
- **Glass morphism**: Các card có backdrop-blur, border mờ, background bán trong suốt
- **Micro-interactions**: Hover effects mượt mà, smooth scroll, fade-in animations khi scroll

### Bảng màu

```
/* Nền */
--bg-primary:       #000000        /* Nền chính - đen tuyệt đối */
--bg-secondary:     #0A0A0A        /* Nền phụ - đen nhẹ hơn */
--bg-card:          #111111        /* Nền card */
--bg-card-hover:    #1A1A1A        /* Nền card khi hover */

/* Chữ */
--text-primary:     #FFFFFF        /* Tiêu đề chính */
--text-secondary:   #A1A1AA        /* Mô tả, body text */
--text-muted:       #71717A        /* Text phụ, metadata */

/* Accent / Glow */
--accent-blue:      #3B82F6        /* Xanh dương chủ đạo */
--accent-purple:    #8B5CF6        /* Tím phụ */
--glow-blue:        rgba(59, 130, 246, 0.15)   /* Glow effect xanh */
--glow-purple:      rgba(139, 92, 246, 0.10)   /* Glow effect tím */

/* Border */
--border-subtle:    rgba(255, 255, 255, 0.06)  /* Viền card mờ */
--border-hover:     rgba(255, 255, 255, 0.12)  /* Viền khi hover */

/* Gradient */
--gradient-hero:    linear-gradient(135deg, #3B82F6 0%, #8B5CF6 50%, #06B6D4 100%)
--gradient-glow:    radial-gradient(ellipse at center, rgba(59,130,246,0.15) 0%, transparent 70%)
```

### Typography

```
/* Hierarchy */
Hero heading:       text-5xl md:text-7xl font-bold tracking-tight leading-[1.1]
Section heading:    text-3xl md:text-5xl font-bold tracking-tight
Sub heading:        text-xl md:text-2xl font-semibold
Body:               text-base md:text-lg text-[#A1A1AA] leading-relaxed
Small/Caption:      text-sm text-[#71717A]
```

- Font chính: `Inter` hoặc `Geist Sans` (sans-serif, hiện đại)
- Heading luôn dùng `font-bold` + `tracking-tight`
- Body text dùng màu secondary (#A1A1AA), KHÔNG dùng trắng cho đoạn văn dài

### Spacing & Layout

```
/* Section padding */
Section:            py-24 md:py-32
Container:          max-w-7xl mx-auto px-6 md:px-8

/* Card */
Card padding:       p-6 md:p-8
Card border:        border border-white/[0.06]
Card radius:        rounded-2xl md:rounded-3xl
Card background:    bg-[#111] hoặc bg-white/[0.03]

/* Grid */
Features grid:      grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6 md:gap-8
```

### Hiệu ứng đặc biệt

```css
/* Glow effect cho hero/card nổi bật */
.glow-effect {
  box-shadow: 0 0 80px rgba(59, 130, 246, 0.15),
              0 0 160px rgba(139, 92, 246, 0.08);
}

/* Glass card */
.glass-card {
  background: rgba(255, 255, 255, 0.03);
  backdrop-filter: blur(12px);
  border: 1px solid rgba(255, 255, 255, 0.06);
}

/* Gradient text cho heading nổi bật */
.gradient-text {
  background: linear-gradient(135deg, #fff 0%, #a1a1aa 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}

/* Subtle dot grid background pattern */
.dot-pattern {
  background-image: radial-gradient(circle, rgba(255,255,255,0.05) 1px, transparent 1px);
  background-size: 24px 24px;
}
```

---

## 📐 Cấu Trúc Trang

### Trang chủ — Sections theo thứ tự:

1. **Navigation Bar**
   - Logo "JamesCR" bên trái (text-based, font-bold)
   - Menu links giữa: Dịch Vụ | Nhóm Giảm Giá | Về Chúng Tôi | Liên Hệ
   - CTA button bên phải: "Liên Hệ Ngay" (accent-blue, rounded-full)
   - Sticky top, backdrop-blur khi scroll, border-bottom subtle

2. **Hero Section**
   - Headline lớn (text-5xl md:text-7xl): *"Dịch Vụ Etsy Chuyên Nghiệp & Săn Mã Giảm Giá Hàng Đầu"*
   - Sub-headline nhỏ hơn (text-lg, text-secondary): mô tả ngắn gọn giá trị
   - 2 CTA buttons: "Khám Phá Dịch Vụ" (filled) + "Tham Gia Nhóm" (outline)
   - Hero visual: card/mockup với glow effect xanh dương (tương tự reference)
   - Background: gradient glow mờ phía sau hero element
   - Badge nhỏ phía trên headline: "✨ Trusted by 500+ sellers"

3. **Trusted By / Social Proof Bar**
   - Dòng logos hoặc badges: "Đã hỗ trợ 500+ sellers" | "4.9★ đánh giá" | "3 năm kinh nghiệm"
   - Layout ngang, text-muted, subtle dividers

4. **Dịch Vụ Etsy Section**
   - Section heading: *"Dịch Vụ Etsy Toàn Diện"*
   - Sub-text mô tả ngắn
   - Grid 2-3 cột, mỗi service là một glass card:
     - **Mở Shop Etsy**: Icon + title + mô tả + "Tìm hiểu thêm →"
     - **Tối Ưu Listing & SEO**: ...
     - **Thiết Kế Mockup & Branding**: ...
     - **Quản Lý & Vận Hành Shop**: ...
     - **Tư Vấn Chiến Lược Etsy**: ...
     - **Xử Lý Vi Phạm & Kháng Cáo**: ...
   - Mỗi card có hover effect: border sáng hơn + translateY nhẹ

5. **Feature Highlight (Left-Right Layout)**
   - 2-3 blocks xen kẽ: text bên trái + visual/mockup bên phải (và ngược lại)
   - Mỗi block giới thiệu chi tiết 1 dịch vụ nổi bật
   - Visual là screenshot/mockup với glow + rounded corners

6. **Nhóm Săn Mã Giảm Giá Section**
   - Section heading: *"Nhóm Săn Mã Giảm Giá Độc Quyền"*
   - Mô tả lợi ích khi tham gia nhóm
   - Cards cho từng nhóm/gói:
     - Tên nhóm, số thành viên, lợi ích chính
     - CTA: "Tham Gia Ngay" hoặc link Telegram/Zalo/Facebook
   - Có thể dùng pricing-card style với glow cho gói nổi bật

7. **Số Liệu / Stats Section**
   - Layout ngang 3-4 cột
   - Số lớn (text-4xl font-bold) + label:
     - "500+" shops đã mở
     - "10,000+" mã giảm giá đã chia sẻ
     - "4.9/5" đánh giá trung bình
     - "3+" năm kinh nghiệm
   - Animated count-up khi scroll vào viewport

8. **Testimonials Section**
   - Heading: *"Khách Hàng Nói Gì"*
   - Grid 2-3 cột hoặc carousel
   - Mỗi testimonial card: avatar + tên + nội dung đánh giá + rating stars
   - Glass card style

9. **FAQ Section**
   - Accordion style, expand/collapse
   - 5-8 câu hỏi thường gặp về dịch vụ Etsy và nhóm săn mã

10. **CTA Section (Bottom)**
    - Heading lớn: *"Sẵn Sàng Bắt Đầu?"*
    - Sub-text + CTA button nổi bật
    - Background glow effect mạnh hơn
    - Tạo urgency: "Đăng ký hôm nay, nhận ưu đãi đặc biệt"

11. **Footer**
    - 4 cột: Về JamesCR | Dịch Vụ | Hỗ Trợ | Liên Hệ
    - Social links (Facebook, Telegram, Zalo, TikTok)
    - Copyright
    - Nền tối hơn hoặc border-top subtle

---

## 📁 Cấu Trúc Thư Mục

```
jamescr-website/
├── app/
│   ├── layout.tsx           # Root layout + fonts + metadata
│   ├── page.tsx             # Trang chủ
│   ├── globals.css          # Tailwind imports + custom styles
│   └── favicon.ico
├── components/
│   ├── layout/
│   │   ├── Navbar.tsx
│   │   └── Footer.tsx
│   ├── sections/
│   │   ├── Hero.tsx
│   │   ├── SocialProof.tsx
│   │   ├── Services.tsx
│   │   ├── FeatureHighlight.tsx
│   │   ├── CouponGroups.tsx
│   │   ├── Stats.tsx
│   │   ├── Testimonials.tsx
│   │   ├── FAQ.tsx
│   │   └── CTA.tsx
│   └── ui/
│       ├── Button.tsx
│       ├── Card.tsx
│       ├── Badge.tsx
│       ├── GlowEffect.tsx
│       └── AnimatedCounter.tsx
├── lib/
│   ├── constants.ts         # Content data, navigation links
│   └── utils.ts             # Helper functions (cn, etc.)
├── public/
│   ├── images/
│   └── icons/
├── tailwind.config.ts
├── next.config.js
├── tsconfig.json
├── package.json
└── CLAUDE.md
```

---

## ✍️ Quy Tắc Code

### General
- Dùng TypeScript strict mode
- Component-based architecture, mỗi section là 1 component riêng
- Tất cả content text lưu trong `lib/constants.ts` để dễ chỉnh sửa
- Responsive: mobile-first, breakpoints: sm(640) → md(768) → lg(1024) → xl(1280)
- Accessibility: semantic HTML, alt text, aria-labels, keyboard navigation

### Component Conventions
- Dùng React Server Components mặc định
- Chỉ thêm `"use client"` khi cần interactivity (animations, state, event handlers)
- Props interface đặt tên: `ComponentNameProps`
- Dùng `cn()` utility (clsx + tailwind-merge) cho conditional classes

### Animation Guidelines
- Dùng Framer Motion cho scroll-triggered animations
- Fade-in + slide-up cho mỗi section khi scroll vào viewport
- Duration: 0.5-0.8s, ease: `[0.16, 1, 0.3, 1]` (custom ease-out)
- Stagger children: 0.1s delay giữa các items
- KHÔNG quá nhiều animation — giữ subtle và elegant
- Hover transitions: `duration-300 ease-out`

### Performance
- Optimize images: next/image với WebP/AVIF
- Lazy load sections below the fold
- Preload font Inter/Geist
- Metadata đầy đủ cho SEO

---

## 🌐 Nội Dung Website (Tiếng Việt)

### Brand Voice
- **Chuyên nghiệp** nhưng **thân thiện**
- Ngôn ngữ rõ ràng, đi thẳng vào giá trị
- Tránh ngôn ngữ quá kỹ thuật, dễ hiểu cho seller mới
- CTA mạnh mẽ, tạo động lực hành động

### SEO Metadata
```
Title:       JamesCR — Dịch Vụ Etsy & Săn Mã Giảm Giá Chuyên Nghiệp
Description: JamesCR cung cấp dịch vụ mở shop Etsy, tối ưu SEO, quản lý shop và nhóm săn mã giảm giá độc quyền. Đồng hành cùng 500+ sellers thành công.
Keywords:    etsy, dịch vụ etsy, mở shop etsy, seo etsy, mã giảm giá, coupon, jamescr
```

---

## ⚠️ Lưu Ý Quan Trọng

1. **KHÔNG dùng light theme** — toàn bộ website là dark theme
2. **KHÔNG dùng màu nền xám nhạt** — chỉ dùng đen (#000) đến (#111)
3. **Glow effects phải subtle** — không quá sáng, không neon quá mức
4. **Text body KHÔNG trắng hoàn toàn** — dùng #A1A1AA cho readability
5. **Spacing phải rộng rãi** — đừng nhồi nhét nội dung, cho các section thở
6. **Mọi interaction phải smooth** — transition-all duration-300
7. **Mobile-first** — test kỹ trên mobile, navbar phải có hamburger menu
8. **Images/Visuals** — nếu chưa có ảnh thực, dùng gradient placeholders với glow effects thay vì stock photos

---

## 🔒 Quy Tắc Bắt Buộc

> [!CAUTION]
> Các quy tắc dưới đây PHẢI được tuân thủ trong suốt quá trình phát triển. Không được bỏ qua.

1. **Screenshot & So sánh** — Sau mỗi thay đổi lớn (hoàn thành section, thay đổi layout, update style), PHẢI chụp screenshot và so sánh trực quan với design reference gốc (ảnh Framer.com đã cung cấp). Đảm bảo:
   - Tông màu đen, glow effects đúng mức
   - Typography hierarchy nhất quán
   - Spacing rộng rãi giống reference

2. **Mobile-Friendly bắt buộc** — Website PHẢI hoạt động tốt trên mọi thiết bị:
   - Navbar: hamburger menu trên mobile, slide-in hoặc full-screen overlay
   - Grid: chuyển từ multi-column → single-column trên mobile
   - Font size: scale hợp lý (không quá nhỏ trên mobile)
   - Touch targets: buttons/links tối thiểu 44×44px
   - Test trên viewport: 375px (iPhone SE), 390px (iPhone 14), 768px (iPad)
   - Không có horizontal scroll trên bất kỳ breakpoint nào

3. **Animation khi scroll cho MỌI section** — Tất cả sections phải có scroll-triggered animation:
   - Dùng Framer Motion `useInView` hoặc `whileInView`
   - Hiệu ứng tối thiểu: fade-in + slide-up (`opacity: 0→1`, `y: 30→0`)
   - Duration: `0.6-0.8s`, ease: `[0.16, 1, 0.3, 1]`
   - Stagger children items: delay `0.1s` giữa mỗi item
   - Animation chỉ chạy 1 lần (`once: true`) — không lặp lại khi scroll ngược
   - Ưu tiên hiệu suất: dùng `transform` và `opacity` thay vì animate layout properties

---

## 🚀 Lệnh Khởi Tạo

```bash
npx create-next-app@latest jamescr-website --typescript --tailwind --eslint --app --src-dir=false --import-alias="@/*"
cd jamescr-website
npm install framer-motion lucide-react clsx tailwind-merge
```
