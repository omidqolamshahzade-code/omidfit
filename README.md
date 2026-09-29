# OMID FIT

نسخه‌ی Progressive Web App اپ OMID FIT برای نصب روی گوشی با GitHub Pages.

## نصب با GitHub

1. یک Repository جدید در GitHub بساز.
2. تمام فایل‌های این پوشه را در ریشه‌ی Repository آپلود کن.
3. از مسیر `Settings → Pages`، گزینه‌ی `Deploy from a branch` را انتخاب کن.
4. Branch را روی `main` و پوشه را روی `/root` بگذار و Save کن.
5. بعد از انتشار، لینک GitHub Pages را با Chrome یا Safari روی گوشی باز کن.
6. از منوی مرورگر گزینه‌ی `Add to Home Screen` یا `Install app` را بزن.

## نکته مهم

- برای نصب PWA، سایت باید با HTTPS باز شود؛ GitHub Pages این مورد را فراهم می‌کند.
- اطلاعات تمرین‌ها در localStorage همان مرورگر ذخیره می‌شود.
- قبل از پاک‌کردن داده‌های مرورگر، از بخش برنامه بکاپ JSON بگیر.
- برای انتشار آپدیت، فایل‌ها را جایگزین کن و مقدار CACHE در `sw.js` را مثلاً به `fitcoach-apex-v2` تغییر بده.
