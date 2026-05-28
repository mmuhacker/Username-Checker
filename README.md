<div align="center">

### 🔍 فحص توفر اليوزرات (متاحات)

꧁ঔৣ☬ Muhannad Daher ☬ঔৣ꧂

أداة احترافية للبحث عن توفر اليوزرات على وسائل التواصل الاجتماعي ومنصات الذكاء الاصطناعي

---

![Version](https://img.shields.io/badge/Version-1.0-blue?style=for-the-badge)

![Platform](https://img.shields.io/badge/Platform-Android%20%7C%20Linux-green?style=for-the-badge&logo=android_<svg role="img" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><title>Kali Linux</title><path d="M12.778 5.943s-1.97-.13-5.327.92c-3.42 1.07-5.36 2.587-5.36 2.587s5.098-2.847 10.852-3.008zm7.351 3.095l.257-.017s-1.468-1.78-4.278-2.648c1.58.642 2.954 1.493 4.021 2.665zm.42.74c.039-.068.166.217.263.337.004.024.01.039-.045.027-.005-.025-.013-.032-.013-.032s-.135-.08-.177-.137c-.041-.057-.049-.157-.028-.195zm3.448 8.479s.312-3.578-5.31-4.403a18.277 18.277 0 0 0-2.524-.187c-4.506.06-4.67-5.197-1.275-5.462 1.407-.116 3.087.643 4.73 1.408-.007.204.002.385.136.552.134.168.648.35.813.445.164.094.691.43 1.014.85.07-.131.654-.512.654-.512s-.14.003-.465-.119c-.326-.122-.713-.49-.722-.511-.01-.022-.015-.055.06-.07.059-.049-.072-.207-.13-.265-.058-.058-.445-.716-.454-.73-.009-.016-.012-.031-.04-.05-.085-.027-.46.04-.46.04s-.575-.283-.774-.893c.003.107-.099.224 0 .469-.3-.127-.558-.344-.762-.88-.12.305 0 .499 0 .499s-.707-.198-.82-.85c-.124.293 0 .469 0 .469s-1.153-.602-3.069-.61c-1.283-.118-1.55-2.374-1.43-2.754 0 0-1.85-.975-5.493-1.406-3.642-.43-6.628-.065-6.628-.065s6.45-.31 11.617 1.783c.176.785.704 2.094.989 2.723-.815.563-1.733 1.092-1.876 2.97-.143 1.878 1.472 3.53 3.474 3.58 1.9.102 3.214.116 4.806.942 1.52.84 2.766 3.4 2.89 5.703.132-1.709-.509-5.383-3.5-6.498 4.181.732 4.549 3.832 4.549 3.832zM12.68 5.663l-.15-.485s-2.484-.441-5.822-.204C3.37 5.211 0 6.38 0 6.38s6.896-1.735 12.68-.717Z"/></svg>)

![Python](https://img.shields.io/badge/Python-3.x-yellow?style=for-the-badge&logo=python)

![License](https://img.shields.io/badge/License-MIT_License-red?style=for-the-badge)

![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge)


---

**المحتويات:**
</div>

- [المميزات](#-المميزات)
- [المنصات المدعومة](#-المنصات-المدعومة)
- [طريقة التثبيت والتشغيل](#-طريقة-التثبيت-والتشغيل)
- [Android — Termux](#-android--termux)
- [Kali Linux](#-kali-linux)
- [طريقة الاستخدام](#-طريقة-الاستخدام)
- [إعدادات Tor](#-إعدادات-tor)
- [اختصارات مهمة](#%EF%B8%8F-اختصارات-مهمة)
- [حفظ النتائج](#-حفظ-النتائج)
- [المطور](#%E2%80%8D-المطور)

---
<div align="center">

## ✨ المميزات
</div>

- 🌐 فحص **32 منصة** دفعة واحدة
- 🤖 توليد يوزرات تلقائياً بثلاث طرق
- 🔒 دعم **Tor** لتجاوز الحظر
- ⛔ إمكانية إيقاف البحث في أي وقت
- 💾 حفظ النتائج في مجلد يختاره المستخدم
- 📋 قراءة يوزرات من ملف txt
- 🌐 فحص يدوي أو تلقائي على كل المنصات دفعة واحدة
- 🔤 دعم كامل للغة العربية في Terminal

---
<div align="center">

## 📱 المنصات المدعومة
</div>


| الفئة | المنصات |
|-------|---------|
| 📱 التواصل الاجتماعي | Facebook, Instagram, Twitter/X, YouTube, Snapchat, Pinterest, LinkedIn, Reddit, Tumblr, Quora, Medium |
| 💻 تقنية وترفيه | GitHub, Steam, DeviantArt, Twitch |
| 🎥 فيديو وبث | Vimeo, Dailymotion |
| 🎵 موسيقى وصور | SoundCloud, Spotify, Flickr |
| ✈️ تواصل | Telegram |
| 🤖 توليد صور AI | Civitai, NightCafe, Leonardo AI, Tensor.Art, DreamStudio, Dreamlike.art, Dreamstime, Lexica.art, Arthub.ai, Krea.ai, Playground AI |

---
<div align="center">
   
## 🚀 طريقة التثبيت والتشغيل

---

## 📱 Android — Termux

</div>

**الخطوة 1 — تثبيت المتطلبات (مرة واحدة فقط)**
```bash
pkg install python tor curl fontconfig rust -y
pip install requests pysocks arabic-reshaper
pip install python-bidi==0.4.2
```

**الخطوة 2 — تثبيت الخط العربي (مرة واحدة فقط)**
```bash
curl -L "https://fonts.gstatic.com/s/notonaskharabic/v33/RrQ5bpV-9Dd1b1OAGA6M9PkyDuVBePeKNaxcsss0Y7bwvc-VaA.ttf" -o ~/.termux/font.ttf
termux-reload-settings
```

> ⚠️ أغلق Termux تماماً وافتحه من جديد بعد تثبيت الخط

**الخطوة 3 — تنزيل الأداة وتشغيلها**
```bash
curl -L "https://raw.githubusercontent.com/mmuhacker/Username-Checker/main/mud.py" -o ~/mud.py
tor &
sleep 5
python ~/mud.py
```

**أو كل شيء في أمر واحد (بعد تثبيت الخط)**
```bash
pkg install python tor curl fontconfig rust -y && pip install requests pysocks arabic-reshaper && pip install python-bidi==0.4.2 && curl -L "https://raw.githubusercontent.com/mmuhacker/Username-Checker/main/mud.py" -o ~/mud.py && tor & sleep 5 && python ~/mud.py
```

---
<div align="center">

## 🐉 Kali Linux
</div>

**الخطوة 1 — تثبيت المتطلبات (مرة واحدة فقط)**
```bash
sudo apt install python3 tor curl fonts-noto-core -y
pip3 install requests pysocks arabic-reshaper python-bidi
```

**الخطوة 2 — تنزيل الأداة**
```bash
curl -L "https://raw.githubusercontent.com/mmuhacker/Username-Checker/main/mud.py" -o ~/mud.py
```

**الخطوة 3 — تشغيل الأداة**
```bash
sudo service tor start
sleep 5
python3 ~/mud.py
```

**أو كل شيء في أمر واحد**
```bash
sudo apt install python3 tor curl fonts-noto-core -y && pip3 install requests pysocks arabic-reshaper python-bidi && curl -L "https://raw.githubusercontent.com/mmuhacker/Username-Checker/main/mud.py" -o ~/mud.py && sudo service tor start && sleep 5 && python3 ~/mud.py
```

---
<div align="center">

## 📖 طريقة الاستخدام
</div>

```
1. اختر المنصة برقمها من القائمة
2. اختر الوضع:
   • ✍️  يدوي  — أدخل يوزر أو عدة يوزرات
   • 🤖 تلقائي — الأداة تولد وتفحص تلقائياً
3. اختر 0 للفحص على كل المنصات:
   • يدوي  — أدخل يوزر واحد يُفحص على 32 منصة
   • تلقائي — توليد يوزرات وفحص كل واحد على 32 منصة
4. اختر 98 لإعدادات Tor
```

---
<div align="center">

## 🔒 إعدادات Tor
</div>

الأداة تكشف Tor تلقائياً عند التشغيل.
لتفعيله يدوياً اختر **98** من القائمة.

| الحالة | المعنى |
|--------|--------|
| 🟢 مفعّل | الطلبات مشفرة وتجاوز الحظر مفعّل |
| 🔴 معطّل | الاتصال المباشر |

---
<div align="center">
   
## ⌨️ اختصارات مهمة
   
</div>

| الاختصار | الوظيفة |
|----------|---------|
| `Volume↓ + C` (Termux) / `Ctrl+C` (Kali) | إيقاف البحث فوراً |
| `0` | فحص على كل المنصات |
| `98` | إعدادات Tor |
| `-1` | خروج |

---
<div align="center">
   
## 📂 حفظ النتائج
   
</div>

عند اختيار حفظ النتائج تظهر ثلاثة خيارات:

```
1. 🏠 المجلد الرئيسي (~)
2. 📥 مجلد التنزيلات (/sdcard/Download)
3. ✍️  مسار مخصص تكتبه أنت
```

---

<div align="center">

## 👨‍💻 المطور

**Muhannad Daher**

[![GitHub](https://img.shields.io/badge/GitHub-mmuhacker-black?style=for-the-badge&logo=github)](https://github.com/mmuhacker)
[![Contact Us](https://img.shields.io/badge/Contact_Us-black?style=for-the-badge&logo=gmail&logoColor=white)](mailto:madarik.ai.info@gmail.com)

</div>

---

- أداة فحص المتاحات المتطورة (32) منصة
- البيئة: Termux (Android) / Kali Linux
- الإصدار: v1.0

---

<div align="center">

**⭐ إذا أعجبتك الأداة، لا تنسَ النجمة! ⭐**

</div>
