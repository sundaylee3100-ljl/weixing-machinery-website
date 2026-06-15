# Wei Xing Machinery Website / 伟星机械网站

Modern bilingual (EN/ZH) website for Yuyao Wei Xing Machinery Co., Ltd.

## Quick Start / 快速预览

```bash
node preview-server.js
```

Then open:
- English: http://localhost:3000/
- Chinese: http://localhost:3000/zh/

## Site Structure / 网站结构

```
weixing-website/
├── index.html              # English homepage
├── css/
│   └── style.css           # Global styles
├── js/
│   └── main.js             # Global scripts
├── products/
│   └── index.html          # Products page (EN)
├── about/
│   └── index.html          # About page (EN)
├── quality/
│   └── index.html          # Quality page (EN)
├── contact/
│   └── index.html          # Contact page (EN)
├── zh/
│   ├── index.html          # Chinese homepage
│   ├── products/
│   │   └── index.html      # Products page (ZH)
│   ├── about/
│   │   └── index.html      # About page (ZH)
│   ├── quality/
│   │   └── index.html      # Quality page (ZH)
│   └── contact/
│       └── index.html      # Contact page (ZH)
├── assets/
│   └── images/             # Place product photos here
├── preview-server.js       # Local dev server
└── README.md
```

## Pages / 页面

| Page | English | Chinese |
|------|---------|---------|
| Home | `/` | `/zh/` |
| Products | `/products/` | `/zh/products/` |
| About Us | `/about/` | `/zh/about/` |
| Quality | `/quality/` | `/zh/quality/` |
| Contact | `/contact/` | `/zh/contact/` |

## Features / 功能特点

- ✅ Responsive design (mobile/tablet/desktop)
- ✅ Bilingual EN/ZH with language switcher
- ✅ WhatsApp floating button
- ✅ Quote request form
- ✅ Product filtering by category
- ✅ Animated counters
- ✅ Scroll animations
- ✅ Sticky header
- ✅ SEO meta tags + hreflang
- ✅ Fast loading (no frameworks, pure HTML/CSS/JS)

## Deployment / 部署方式

### Option 1: Static Hosting (Recommended)
Upload the entire folder to any static host:
- **Netlify**: drag & drop the folder
- **Vercel**: `vercel --prod`
- **Cloudflare Pages**: connect git repo
- **GitHub Pages**: push to gh-pages branch

### Option 2: Traditional Web Host
Upload via FTP to your web hosting provider.

### Option 3: Alibaba Cloud / 阿里云
Upload to OSS + CDN for China access (requires ICP filing).

## Customization / 自定义

1. **Replace phone/email**: Search for `XXXX` in all HTML files
2. **Add product photos**: Place images in `assets/images/` and update `<img>` tags
3. **Update WhatsApp number**: Search for `8613800000000` and replace
4. **Add Google Maps**: Replace map placeholder in contact page
5. **Connect form**: Update form action in contact pages to your backend/Formspree/etc.
