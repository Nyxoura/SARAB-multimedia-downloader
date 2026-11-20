# سراب | SARAB

**تطبيق سطح مكتب سريع ومينيمال لتحميل ومعالجة الوسائط محلياً على جهازك**

**A fast, minimalist desktop application for downloading and processing media locally**

**سراب (SARAB)** تطبيق سطح مكتب متعدد المنصات مبني باستخدام **Tauri** و**React** و**TypeScript**، صُمّم ليمنحك تحكماً مباشراً وسريعاً في تحميل ومعالجة الوسائط محلياً على جهازك دون تعقيد أو إعلانات أو إرسال بياناتك إلى خوادم خارجية.

### أبرز المزايا

* **معالجة محلية بالكامل (100% Local):** يعمل التطبيق على جهازك فقط؛ لا يحتفظ ببياناتك ولا يرسلها إلى خوادم خارجية.

* **واجهة ثنائية اللغة:** دعم كامل للغتين العربية والإنجليزية.

* **أدوات عملية للوسائط:** قص المقاطع بدقة، واستخراج الكوكيز تلقائياً، والاعتماد على أدوات المعالجة المحلية (`yt-dlp`، `ffmpeg`، `ffprobe`، `deno`).

* **أداء عملي وتجربة نظيفة:** تصميم يركز على الوضوح والسرعة وسهولة الاستخدام اليومي.

### التشغيل والبناء محلياً

#### المتطلبات

* **Node.js** و **npm**

* **Rust** و **Cargo** (لمنصة Tauri)

* أدوات المعالجة المطلوبة إن لم تكن مضمّنة في بيئة البناء: `yt-dlp`، `ffmpeg`، `ffprobe`، `deno`.

#### خطوات التشغيل

```
# 1. تثبيت حزم الواجهة الأمامية
npm install

# 2. تشغيل التطبيق في وضع التطوير
npm run tauri dev

# 3. بناء نسخة التوزيع النهائية
npm run tauri build

```

### الإصدارات (Releases)

النسخ الجاهزة وملفات التثبيت متوفرة في قسم **Releases** داخل المستودع، حيث يُنشر كل إصدار مع ملاحظات التحديث الخاصة به.

### إخلاء مسؤولية واستخدام مسؤول

يُستخدم التطبيق لمعالجة وتحميل المحتوى المصرح لك بالوصول إليه أو تحميله وفقاً للقوانين المعمول بها وشروط المنصات المعنية.

## English

**SARAB (سراب)** is a cross-platform desktop application built with **Tauri**, **React**, and **TypeScript**, engineered for fast, distraction-free local media downloading and processing—with zero external data collection or server retention.

### Key Highlights

* **Strictly Local Execution:** Runs directly on your machine without storing or transmitting your data to external servers.

* **Bilingual Experience:** Full support for both Arabic and English interfaces.

* **Practical Media Capabilities:** Clip trimming, automated cookie extraction, and local media pipelines powered by `yt-dlp`, `ffmpeg`, `ffprobe`, and `deno`.

* **Clean, Focused Craft:** Minimalist desktop workflows designed for speed, clarity, and reliability.

### Local Setup & Build

#### Prerequisites

* **Node.js** & **npm**

* **Rust** & **Cargo** (for Tauri)

* Required media binaries if not bundled in your build environment: `yt-dlp`, `ffmpeg`, `ffprobe`, and `deno`.

#### Commands

```
# 1. Install frontend dependencies
npm install

# 2. Run in development mode
npm run tauri dev

# 3. Build production release
npm run tauri build

```

### Releases

Pre-built installers and release packages are published under the **Releases** tab along with changelog notes for each version.

### Disclaimer

Use this software responsibly and only with media or sources you have the right or authorization to access and process in compliance with applicable laws and platform terms.

**سراب (SARAB)** — محلي • سريع • واضح

**Local • Fast • Clean**
