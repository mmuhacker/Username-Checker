<div align="center">

### 🔍 فحص توفر اليوزرات (متاحات)

꧁ঔৣ☬ Muhannad Daher ☬ঔৣ꧂

أداة احترافية للبحث عن توفر اليوزرات على وسائل التواصل الاجتماعي ومنصات الذكاء الاصطناعي

---

![Version](https://img.shields.io/badge/Version-1.0-blue?style=for-the-badge)

![Platform](https://img.shields.io/badge/Platform-Android%20%7C%20Linux-green?style=for-the-badge&logo=android)20%![Platform](https://img.shields.io/badge/Platform-Android%20%7C%20Linux-green?style=for-the-badge&logo=linux)


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
