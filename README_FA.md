# BARDIA AI v2 — نصب ساده روی گوشی

این نسخه عمداً APK نیست؛ یک Web App قابل نصب است تا مشکل Android Studio و SDK را دور بزنیم.

## نصب روی اندروید
1) این فایل‌ها را در یک ریپازیتوری GitHub آپلود کن.
2) در GitHub برو به `Settings → Pages` و Source را روی `GitHub Actions` بگذار.
3) Workflow را اجرا کن. بعد لینک `https://USERNAME.github.io/REPOSITORY/` را با Chrome گوشی باز کن و از منوی Chrome گزینه `Add to Home screen` / `Install app` را بزن.

## اتصال دیتای زنده
در خود اپ، API Key سرویس Twelve Data را وارد کن. داده‌های `XAU/USD` با تایم‌فریم 5 دقیقه گرفته می‌شود.

منطق سیگنال:
EMA200 + RSI14 + BOS10 + FVG8 + Order Block8 + ATR14
SL = بر اساس OB/ATR
TP2 = RR 2
Signal-only = روشن

## نکته مهم
نسخه فعلی فقط سیگنال می‌دهد و به MT5 یا بروکر سفارش ارسال نمی‌کند.
کلید API در Local Storage مرورگر نگهداری می‌شود.
