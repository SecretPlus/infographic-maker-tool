# تولیدکننده پرامپت اینفوگرافیک | Infographic Prompt Generator

یک ابزار تک‌فایلی HTML که متن خام کپی‌شده از صفحه محصول یک فروشگاه اینترنتی را می‌گیرد و یک پرامپت تمیز، مینیمال و آماده برای مدل‌های تولید تصویر هوش مصنوعی (مثل Gemini "Nano Banana" یا GPT Image) می‌سازد تا یک اینفوگرافیک مربعی از محصول تولید شود.

A single-file HTML tool that takes raw text copied directly from a store's product page and turns it into a clean, minimal prompt ready for AI image models (e.g. Gemini "Nano Banana" or GPT Image) to generate a square product infographic.

Live demo:** [secretplus.github.io/infographic-maker-tool](https://secretplus.github.io/infographic-maker-tool)


**دمو زنده : [secretplus.github.io/infographic-maker-tool](https://secretplus.github.io/infographic-maker-tool)

<img width="827" height="730" alt="Screenshot_1" src="https://github.com/user-attachments/assets/15bed03b-8bcd-43cd-b236-5b1a8be0b3b7" />

---

## ✨ امکانات | Features

**فارسی**
- تصفیه خودکار متن خام کپی‌شده: منو، فوتر، قیمت، تخفیف، محصولات مشابه، نظرات کاربران و... به‌طور خودکار حذف می‌شوند
- کار می‌کند حتی وقتی خط‌های متن هنگام کپی به‌هم بریزند (بدون newline)
- تشخیص هوشمند نام برند و مدل محصول
- دسته‌بندی خودکار مشخصات کلیدی بر اساس نوع محصول (لپ‌تاپ در مقابل گوشی/تبلت)
- برای گوشی و تبلت: سیم‌کارت، نسل شبکه (4G/5G)، استاندارد مقاومت IPxx و سرعت شارژ هم نمایش داده می‌شود
- ساده‌سازی نام پردازنده و گرافیک برای عموم مردم (مثلاً `Snapdragon 8 Elite Gen 5` به‌جای `Qualcomm SM8850-1-AD Snapdragon 8 Elite Gen 5`)
- ۸ سبک بصری آماده (مینیمال، تاریک، طلایی، سایبرپانک، گرادیان، رترو ۸۰، ایزومتریک رنگی، بیزینس نموداری)
- خروجی به سه زبان: فارسی + برند انگلیسی / کاملاً فارسی / کاملاً انگلیسی
- رابط کاربری دوزبانه (فارسی/انگلیسی) با دکمه سوئیچ سریع
- بدون نیاز به سرور یا نصب — فقط یک فایل HTML

**English**
- Automatically strips noise from raw pasted text: menus, footers, prices, discounts, related products, reviews, etc.
- Works even when line breaks are lost during copy/paste
- Smart brand + model name detection
- Adapts which specs it shows based on product type (laptop vs. phone/tablet)
- For phones/tablets: also surfaces SIM count, network generation (4G/5G), IP water/dust rating, and charging speed
- Simplifies chipset/GPU names for a general audience (e.g. `Snapdragon 8 Elite Gen 5` instead of `Qualcomm SM8850-1-AD Snapdragon 8 Elite Gen 5`)
- 8 built-in visual styles (Minimal, Dark, Gold, Cyberpunk, Gradient, Retro 80s, Colorful Isometric, Business Chart)
- Output in 3 languages: Persian + English brand / fully Persian / fully English
- Bilingual UI (Persian/English) with a one-click language toggle
- No server or install required — a single static HTML file

---

## 🌐 سایت‌های پشتیبانی‌شده | Supported sites

بهترین عملکرد با محتوای کپی‌شده مستقیم از این ۴ سایت است — Best results with content copied directly from these 4 sites:

| سایت / Site | آدرس / URL |
|---|---|
| دیجی‌کالا / Digikala | https://www.digikala.com |
| بی‌پی‌آر شاپ / bprshop | https://www.bprshop.com |
| GSMArena | https://www.gsmarena.com |
| NanoReview | https://nanoreview.net |

سایر سایت‌ها هم معمولاً کار می‌کنند، اما دقت استخراج فقط برای این ۴ سایت تضمین شده است.
Other sites will often work too, but extraction accuracy is only guaranteed for these 4.

---

## 🚀 استفاده | Usage

**فارسی**
1. فایل `index.html` را باز کنید
2. کل متن صفحه محصول را از یکی از سایت‌های بالا کپی کنید (Ctrl+A سپس Ctrl+C روی صفحه محصول)
3. متن را در کادر ورودی جای‌گذاری کنید
4. زبان خروجی و سبک بصری دلخواه را انتخاب کنید
5. روی «تولید پرامپت» بزنید و نتیجه را کپی کنید

**English**
1. Open `index.html`
2. Copy the entire product page text from one of the sites above (Ctrl+A then Ctrl+C on the product page)
3. Paste it into the input box
4. Pick your output language and visual style
5. Click "Generate Prompt" and copy the result

---

## 🖥️ اجرای محلی | Running locally

هیچ نصبی لازم نیست — فقط فایل `index.html` را در مرورگر باز کنید.
No installation needed — just open `index.html` in any browser.

```bash
git clone <repo-url>
cd <repo-folder>
open index.html   # macOS
# or just double-click the file
```

---

## 📦 دیپلوی رایگان با GitHub Pages | Free deploy with GitHub Pages

1. این ریپازیتوری را Fork یا آپلود کنید — Fork or upload this repository
2. به **Settings → Pages** بروید — Go to **Settings → Pages**
3. Branch را روی `main` و پوشه را روی `/ (root)` تنظیم کنید — Set branch to `main` and folder to `/ (root)`
4. لینک شما آماده می‌شود — Your link will be ready at:
   `https://<username>.github.io/<repo-name>/`

---

## ⚠️ محدودیت‌های شناخته‌شده | Known limitations

**فارسی**
- در ورودی‌های به‌هم‌ریخته (بدون خط جدید) از دیجی‌کالا، گاهی عدد اندازه صفحه‌نمایش (مثل «۶.۳ اینچ») جا می‌ماند، هرچند نوع صفحه‌نمایش درست نمایش داده می‌شود
- برای صفحات با چند گزینه پیکربندی (مثل NanoReview که چند مدل CPU/RAM لیست می‌کند)، اولین گزینه به‌عنوان پیکربندی پایه انتخاب می‌شود

**English**
- On heavily jumbled Digikala input (no line breaks), the display-size number (e.g. "6.3 inch") can occasionally be dropped, though the display type still shows correctly
- For pages with multiple configuration options (like NanoReview listing several CPU/RAM choices), the first option is taken as the base configuration

---

## 🛠️ ساخته‌شده با | Built with

فقط HTML + Tailwind CSS (از طریق CDN) + جاوااسکریپت خالص — بدون هیچ فریم‌ورک یا وابستگی build.
Plain HTML + Tailwind CSS (via CDN) + vanilla JavaScript — no framework or build step.



