<div align="center">

# 🛡️ کیمرای آهنین | IronKimera
### سامانه پیشرفته شبکه ابری و دژ پروکسی متصل به پایگاه‌داده توزیع‌شده Cloudflare D1
**Next-Generation Edge Computing Proxy & Web Dashboard Powered by Cloudflare Workers & D1**

[![License: MIT](https://img.shields.io/badge/License-MIT-amber.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![Cloudflare Workers](https://img.shields.io/badge/Cloudflare-Workers_&_D1-orange?style=for-the-badge&logo=cloudflare)](https://workers.cloudflare.com/)
[![Protocols](https://img.shields.io/badge/Protocols-VLESS%20%7C%20Trojan%20%7C%20SS-blueviolet?style=for-the-badge)](#پروتکل‌های-پشتیبانی‌شده)
[![Human Rights](https://img.shields.io/badge/UN%20UDHR-Article%2019-success?style=for-the-badge)](https://www.un.org/en/about-us/universal-declaration-of-human-rights)
[![Anti-Abuse](https://img.shields.io/badge/Protection-Anti--AI%20%26%20Zero--SPOF-blue?style=for-the-badge)](#امنیت-و-حفاظت-سورس)

<br/>

![IronKimera Banner](bot_banner.jpg)

<br/>

**[🌐 دمو و پیشخوان](#امکانات-و-ویژگی‌ها) • [🤖 ربات استقرار خودکار](#-استقرار-سریع-از-طریق-ربات-تلگرام) • [🚀 نصب دستی](#-روش-دوم-استقرار-دستی-در-داشبورد-کلودفلر) • [⚖️ بیانیه حقوقی](#-بیانیه-حقوقی-و-پژوهشی--legal-disclaimer)**

---

</div>

## ⚖️ بیانیه حقوقی و پژوهشی | Legal & Educational Disclaimer

> [!NOTE]
> ### 🇺🇳 Article 19 — UN Universal Declaration of Human Rights
> *"Everyone has the right to freedom of opinion and expression; this right includes freedom to hold opinions without interference and to seek, receive and impart information and ideas through any media and regardless of frontiers."*

```markdown
LEGAL NOTICE:
This repository is an open-source research and educational project dedicated to distributed edge computing,
Cloudflare Workers runtime analysis, and network protocol diagnostics.
It is developed in strict compliance with the UN Universal Declaration of Human Rights (Article 19).
The software is provided "AS IS", without warranty of any kind, express or implied.
The maintainers assume no liability for misuse, third-party operational disruptions, or regulatory non-compliance.
```

> **فارسی:**  
> این پروژه یک ابزار تحقیقاتی و دانشگاهی متن‌باز در حوزه پردازش لبه ابری (Edge Computing) و بهینه‌سازی مسیرهای ترافیکی شبکه است. توسعه و انتشار این بسته منحصراً در راستای ترویج حق همگانی دسترسی آزاد به تبادل اطلاعات طبق ماده ۱۹ اعلامیه جهانی حقوق بشر سازمان ملل متحد صورت گرفته و عاری از هرگونه اهداف انتفاعی یا بدافزاری است.

---

## ✨ امکانات و ویژگی‌های کلیدی

- ⚡ **هسته توزیع‌شده Cloudflare Workers:** اجرای بی‌درنگ روی نزدیک‌ترین پاپ‌سایت‌های کلودفلر با تأخیر نزدیک به صفر.
- 🗄️ **پایگاه‌داده توزیع‌شده D1:** ذخیره‌سازی پیکربندی‌ها، توکن‌ها و وضعیت نودها به صورت رمزنگاری‌شده در دیتابیس بومی کلودفلر (بدون نیاز به سرور خارجی یا KV).
- 🌐 **پشتیبانی چند پروتکله:** پیاده‌سازی کامل استانداردهای **VLESS (WS / gRPC / TCP)**، **Trojan** و **Shadowsocks** به صورت همزمان.
- 🎯 **استخر غنی آی‌پی‌های تمیز:** شامل بیش از **۳۷,۰۰۰ ساب‌نت و دامنه تمیز کلودفلر** با چینش کامپیوتر-تصادفی (Fisher-Yates) جهت جلوگیری از شناسایی امضای ترافیکی.
- 🌍 **پروکسی‌های VIP اختصاصی:** پشتیبانی از تونل‌های خروجی با کیفیت بالا برای بیش از ۱۵ کشور مطرح (آلمان، کانادا، آمریکا، ترکیه، هلند، انگلیس، امارات و ...).
- 🎨 **پیشخوان وب لوکس (Modern Dashboard):** رابط کاربری با طراحی Glassmorphism، تم تاریک اختصاصی کیمرا، مدیریت زنده نودها و تولید آنی لینک‌های اشتراک (Subscription).
- 🔒 **حفاظت ضد مهندسی معکوس (Anti-AI & AST Hardening):** کامپایل خودکار سورس با بیش از ۲۰۰ متغیر نویز و قفل‌گذاری روی Account ID مالک پروژه جهت عقیم‌سازی سرقت سورس توسط افراد سودجو.
- 🛡️ **استقلال ۱۰۰٪ و بدون تک‌نقطه شکست (Zero-SPOF):** قطع کامل هرگونه وابستگی به سرورهای ثالث؛ پروژه کاملاً مستقل روی حساب کلودفلر شما اجرا می‌شود.

---

## 📂 ساختار دارایی‌ها و منابع مخزن

```bash
├── bot_banner.jpg          # بنر سینمایی پیش‌نمایش تلگرام و معرفی پروژه (16:9)
├── welcome_banner.jpg      # نشان اختصاصی کیمرای باستانی-مکانیکی (Cyber Beast)
├── IronKimera.svg          # لوگوی وکتور رسمی پروژه (Dark Obsidian & Glowing Amber)
├── ips.txt                 # استخر آی‌پی‌های تمیز شافل‌شده (بیش از ۳۷ هزار ردیف)
├── vip-list.json           # لیست متادیتا و شاخص کشورهای دارای پروکسی خروجی
├── proxy_vip/              # استخر پروکسی‌های خروجی فعال تفکیک‌شده بر اساس کشور
│   ├── DE.txt              # سرورهای آلمان (SOCKS5)
│   ├── US.txt              # سرورهای آمریکا (SOCKS5)
│   ├── NL.txt              # سرورهای هلند (SOCKS5)
│   ├── TR.txt              # سرورهای ترکیه (SOCKS5)
│   ├── GB.txt              # سرورهای انگلستان (SOCKS5)
│   └── ...                 # سایر کشورها (CA, IT, NO, SE, KZ, UZ, ...)
├── scanner.txt             # اسکریپت تست پینگ و سلامت‌سنجی محلی نودها
└── relay.sh                # اسکریپت راه‌اندازی سریع سرورهای رله خروجی (GOST Relay)
```

---

## 🚀 روش‌های استقرار و نصب

### روش اول: استقرار خودکار از طریق ربات تلگرام (پیشنهادی)

ساده‌ترین روش برای راه‌اندازی پنل بدون نیاز به دانش فنی:

1. ربات استقرار خودکار **IronKimera Deployer** را اجرا کرده یا وارد آن شوید.
2. دستور `/start` را ارسال کنید.
3. یک **Cloudflare API Token** که دارای دسترسی‌های `Workers: Edit` و `D1: Edit` باشد را به ربات بفرستید.
4. ربات به طور خودکار:
   - دیتابیس D1 را می‌سازد.
   - کدها را به صورت ضد سرقت و قفل‌شده روی حساب شما کامپایل می‌کند.
   - ورکر را دیپلوی کرده و لینک پیشخوان اختصاصی و آدرس راه‌اندازی رمز اولیه (`/setup`) را به شما تحویل می‌دهد.

---

### روش دوم: استقرار دستی در داشبورد کلودفلر

اگر ترجیح می‌دهید ورکر را دستی نصب کنید:

1. وارد [داشبورد کلودفلر](https://dash.cloudflare.com) شوید.
2. از منوی سمت چپ به مسیر **Storage & Databases** > **D1** بروید و یک پایگاه‌داده به نام `ironkimera_db` بسازید.
3. به بخش **Workers & Pages** بروید و دکمه **Create application** > **Create Worker** را بزنید.
4. وارد تنظیمات ورکر شوید (**Settings** > **Bindings**) و یک متغیر بایندینگ D1 اضافه کنید:
   * **Variable name:** `DB`
   * **D1 database:** دیتابیس ساخته‌شده در مرحله ۲ (`ironkimera_db`).
5. به تب **Code** بروید، محتویات فایل آماده `worker.js` را در ویرایشگر کپی کرده و **Deploy** را بزنید.
6. دامنه اختصاصی ورکر خود را باز کرده و با رفتن به مسیر `/setup` رمز عبور مدیریت پیشخوان را مشخص کنید.

---

## ⚙️ متغیرهای محیطی ورکر (Environment Variables)

در صورت نیاز به سفارشی‌سازی رفتارهای ورکر، متغیرهای زیر در بخش **Settings > Variables** ورکر قابل تعریف هستند:

| نام متغیر | نوع | مقدار پیش‌فرض | توضیحات |
| :--- | :---: | :---: | :--- |
| `DB` | D1 Binding | *(الزامی)* | بایندینگ پایگاه‌داده توزیع‌شده D1 |
| `ACCOUNT_ID` | String | `auto` | شناسه حساب کلودفلر مالک پروژه (جهت قفل ضد سرقت) |
| `UPSTREAM_ASSETS_BASE_URL` | String | `GitHub Raw URL` | آدرس خام مخزن گیت‌هاب شما جهت دریافت آی‌پی‌های تمیز و پروکسی‌های VIP |
| `PANEL_PATH` | String | `/panel` | مسیر دلخواه دسترسی به پیشخوان مدیریت |

---

## 🔒 امنیت و حفاظت سورس (Anti-Abuse & Anti-AI)

این پروژه از موتور پکینگ پیشرفته `packer.js` بهره می‌برد:
1. **قفل حساب کاربری (Account Lock):** سورس کامپایل‌شده تنها در صورت تطابق با `ACCOUNT_ID` مجاز فعال می‌شود و کپی‌کردن آن در اکانت‌های متفرقه بی‌اثر خواهد بود.
2. **محفظه Base64 و نویزهای انحرافی:** کد اصلی با بیش از ۲۰۰ متغیر نویز و توابع چندگانه در یک بستر بیش از ۱ مگابایتی محافظت شده است که هم اسکنرهای کلودفلر را به دلیل عدم وجود کلیدواژه‌های خام دور می‌زند و هم با فراتر رفتن از سقف توکن هوش‌های مصنوعی، امکان دیکود خودکار را خنثی می‌کند.
3. **رمزنگاری پسورد در پایگاه‌داده:** هیچ رمز پیش‌فرضی درون سورس وجود ندارد و کلید عبور تنها از طریق فرآیند تأیید اولیه (`/setup`) به شکل رمزنگاری‌شده در D1 ذخیره می‌گردد.

---

## 🤝 مشارکت و بهبود مستمر

مشارکت در بهبود این پروژه متن‌باز برای همه پژوهشگران و توسعه‌دهندگان آزاد است:
- جهت ارسال باگ یا پیشنهاد قابلیت جدید، یک [Issue](https://github.com) ثبت کنید.
- جهت افزودن ساب‌نت‌های جدید آی‌پی تمیز یا سرورهای رله خروجی، [Pull Request](https://github.com) ارسال فرمایید.

---

## 📄 لایسنس (License)

این پروژه تحت قوانین **لایسنس متن‌باز [MIT](https://opensource.org/licenses/MIT)** منتشر شده است. استفاده و اشتراک‌گذاری آزاد است، مشروط بر حفظ بیانیه حق چاپ و سلب مسئولیت سازندگان.

<div align="center">
  <sub>ساخته‌شده با افتخار برای آزادی اینترنت و پایداری ارتباطات 🛡️</sub>
</div>
