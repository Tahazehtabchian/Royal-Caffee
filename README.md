# Royal Caffee — Digital Menu Demo

**Live demo →** https://taz-cafe-menu.vercel.app

A single-file digital menu for a cafe, in Persian with a full right-to-left layout.
There is no backend: the menu, cart and admin panel all run in the browser on
sample data, so the whole thing is one HTML file that works from a link or straight
off disk.

### What's inside

- **Menu** — 16 items across four categories (hot drinks, cold drinks, cake &
  dessert, food), with search, category tabs, and "best-seller" / "vegetarian"
  quick filters.
- **Ordering** — tap any item for a quick-view (photo, description, quantity
  stepper), add to cart, and check out to a confirmation screen with an order
  number. Toast notifications replace browser pop-ups throughout.
- **QR / table ordering** — a link scanned with `?table=5` in it shows "Table 5"
  in the header and on the order confirmation, so each table's QR code can carry
  its own number.
- **Admin panel** (tap "پنل", password `1234`) — add, edit and delete menu items,
  and generate a downloadable QR code for any table straight from the browser
  (no server, no external QR service).

### Built with

Plain HTML/CSS/JS, no build step, no dependencies — Tailwind CSS (CDN), Font
Awesome, Vazirmatn font and the `qrcodejs` library, all loaded from public CDNs.
Runs by opening `index.html` directly, or from any static host (this demo is on
Vercel).

### About the content

This is a sample built to demonstrate the interface, not a real cafe's ordering
system: menu items, prices and photos are all placeholders, and "Royal Caffee" is
a placeholder name. The admin password is intentionally simple since this is a demo.

---

<div dir="rtl">

# رویال کافه — نمونه‌ی منوی دیجیتال

**مشاهده‌ی دمو ←** https://taz-cafe-menu.vercel.app

یک منوی دیجیتال تک‌فایل برای کافه، کاملاً فارسی و راست‌چین. بک‌اند ندارد: منو،
سبد خرید و پنل مدیریت همگی با داده‌های نمونه در خود مرورگر کار می‌کنند؛ کل پروژه
یک فایل HTML است که هم از روی لینک و هم مستقیم از روی دیسک اجرا می‌شود.

### چه چیزهایی دارد

- **منو** — ۱۶ آیتم در چهار دسته (نوشیدنی گرم، نوشیدنی سرد، کیک و دسر، غذا)،
  همراه با جست‌وجو، تب‌های دسته‌بندی و فیلترهای سریع «پرفروش» و «گیاهی».
- **سفارش‌گیری** — با لمس هر آیتم، پیش‌نمایش سریع (عکس، توضیحات، شمارشگر تعداد)
  باز می‌شود، آیتم به سبد اضافه می‌شود و در انتها یک صفحه‌ی تأیید با شماره‌ی
  سفارش نمایش داده می‌شود. به‌جای پاپ‌آپ‌های مرورگر، همه‌جا از نوتیفیکیشن‌های
  داخل صفحه استفاده شده.
- **سفارش با کیوآر / تفکیک میز** — لینکی که با `?table=5` اسکن شود، «میز ۵» را
  در هدر و روی تأییدیه‌ی سفارش نشان می‌دهد؛ یعنی کیوآر هر میز می‌تواند شماره‌ی
  خودش را داشته باشد.
- **پنل مدیریت** (دکمه‌ی «پنل»، رمز `1234`) — افزودن، ویرایش و حذف آیتم‌های منو،
  و ساخت کیوآر کدِ قابل‌دانلود برای هر میز مستقیماً در مرورگر (بدون سرور یا
  سرویس بیرونی).

### با چه چیزی ساخته شده

HTML/CSS/JS ساده، بدون مرحله‌ی build و بدون هیچ وابستگی نصبی — Tailwind CSS
(از طریق CDN)، Font Awesome، فونت وزیرمتن و کتابخانه‌ی `qrcodejs`، همگی از CDN
عمومی بارگذاری می‌شوند. با باز کردن مستقیم `index.html` یا روی هر میزبان
استاتیکی اجرا می‌شود (این دمو روی Vercel است).

### درباره‌ی محتوا

این یک نمونه برای نمایش رابط کاربری است، نه سامانه‌ی سفارش‌گیری یک کافه‌ی واقعی:
آیتم‌های منو، قیمت‌ها و عکس‌ها همگی نمونه‌اند و «رویال کافه» یک نام جای‌گذاری‌شده
است. رمز پنل مدیریت هم عمداً ساده انتخاب شده چون این یک نسخه‌ی نمایشی است.

</div>
