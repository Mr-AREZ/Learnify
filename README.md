# Learnify — وب‌سایت معلم خصوصی (مینی‌پروژه مرحله ۵)

فقط HTML5 + CSS3 (بدون JavaScript، بدون Bootstrap/Tailwind).

## اجرا
فایل `index.html` را در مرورگر باز کن.

## ساختار
- `index.html` — ۹ بخش اصلی + پکیج‌ها و سوالات متداول (از تصویر مرجع)
- `css/style.css` — Tokens → Base → Layout → Components → Media Queries
- `fonts/` — Vazirmatn (OFL)
- `assets/img/` — همه عکس‌ها از تصویر مرجع برش خورده‌اند (کیفیت پایین‌اند؛ با عکس واقعی جایگزین کن)

## نگاشت به حوزه‌های مرحله ۵
- Responsive: Mobile First، `rem/%/vw`، `.container` با `max-width: 80rem`، بدون اسکرول افقی در ۳۲۰ تا ۱۹۲۰px
- Media Queries: ۶۰۰ / ۶۸۰ / ۹۰۰ / ۱۱۲۰ / ۱۲۰۰ + `orientation: landscape`، `hover: hover`، `prefers-reduced-motion`
- Flexbox: هدر، Hero، دکمه‌ها، آمار Hero (`flex: 1 1 10rem`)، تماس، داخل کارت‌ها
- Grid: دوره‌ها (`repeat(auto-fit, minmax(min(100%,19rem),1fr))`)، روش تدریس، نظرات، مقالات، آمار؛ `min-width: 0` روی آیتم‌ها
- Container Queries: `.course-slot` (container: course) و `.tutor-slot` (container: tutor) — کارت معلم هم در بخش «درباره» (عریض) و هم در کنار فرم (باریک) استفاده شده
- Typography: `clamp()` برای H1–متن جانبی، `text-wrap: balance`، `overflow-wrap: anywhere`، `max-width` برای متن

## جایگزینی محتوا
نام «امیر رضایی»، مدارک، شماره و ایمیل نمونه‌اند. `hero.jpg` و `teacher.jpg` را با عکس واقعی عوض کن.
