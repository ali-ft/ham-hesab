# راهنمای ساخت و اشتراک فایل Figma

خروجی رسمی تسک باید **لینک Figma با دسترسی View** برای این ایمیل باشد:

`hana.pkhki.qanbari@gmail.com`

## ساختار پیشنهادی صفحات داخل Figma

1. **Cover** — نام محصول، نام شما (علی فتی)، عنوان تسک مهیمن
2. **Product Brief** — خلاصه مسئله و راه‌حل (از `product-brief.md`)
3. **User Flow** — دیاگرام جریان کاربر (از بخش Flow در `presentation/index.html`)
4. **Use Cases** — جدول/کارت‌های UC-01 تا UC-10
5. **Wireframes** — مسیر: Home → نوع قرض → انتخاب نفر → مبلغ → بررسی → موفقیت
6. **UI Hi-Fi** — حداقل دو صفحه: **داشبورد** و **ثبت مبلغ**
7. **Prototype** (اختیاری ولی قوی) — لینک کردن فریم‌ها با Prototype mode

## روش سریع A — اسکرین‌شات از ارائه و پروتوتایپ

1. فایل‌ها را باز کنید:
   - `presentation/index.html`
   - `prototype/app.html`
2. در مرورگر، هر بخش/صفحه را اسکرین بگیرید (یا Extension مثل GoFullPage).
3. در Figma: `File → New design file`
4. تصاویر را Paste کنید داخل فریم‌های جدا (Frame per screen، عرض موبایل ۳۹۰).
5. روی تصاویر Wireframe و UI، لیبل بگذارید (WF-01, UI-Home, …).
6. برای Flow، از بخش SVG ارائه اسکرین بگیرید یا با FigJam / connectors بازسازی کنید.

## روش سریع B — بازسازی با کامپوننت (تمیزتر برای ارزیابی)

1. فریم موبایل ۳۹۰×844 بسازید.
2. رنگ‌ها را از استایل ارائه کپی کنید:
   - Brand: `#0F6B5C`
   - Ink: `#14201B`
   - Surface: `#F3F6F4`
   - Lend: `#1F8A6E`
   - Borrow: `#C45C4A`
3. فونت فارسی: **Vazirmatn** (از Google Fonts در Figma نصب/اضافه شود).
4. دو صفحه UI را pixel-close از `prototype/app.html` بازسازی کنید.
5. بقیه مسیر را Wireframe ساده (خاکستری) بگذارید.

## اشتراک‌گذاری (حتماً)

1. دکمه **Share** در Figma
2. ایمیل: `hana.pkhki.qanbari@gmail.com`
3. Permission: **can view**
4. لینک عمومی را هم می‌توانید روی «Anyone with the link → can view» بگذارید تا مشکل دسترسی پیش نیاید
5. لینک را از طریق فرم https://cdoo.ir/CgvgeC ارسال کنید

## چک‌لیست قبل از ارسال

- [ ] User Flow کامل است
- [ ] Use Caseها با توضیح اکشن آمده‌اند
- [ ] مسیر ثبت قرض از Home تا Success مشخص است
- [ ] حداقل ۲ صفحه UI رنگی دارید
- [ ] دسترسی View برای ایمیل خواسته‌شده فعال است
- [ ] نام شما روی کاور فایل هست
