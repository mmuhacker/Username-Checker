<div align="center">

### 🔍 فحص توفر اليوزرات (متاحات)

꧁ঔৣ☬ Muhannad Daher ☬ঔৣ꧂

أداة احترافية للبحث عن توفر اليوزرات على وسائل التواصل الاجتماعي ومنصات الذكاء الاصطناعي

---

![Version](https://img.shields.io/badge/Version-1.0-blue?style=for-the-badge)




![Platform](https://img.shields.io/badge/Platform-Kali_Linux_&_Android-green?style=for-the-badge&logo=android)

![Platform](https://img.shields.io/badge/Platform-Kali_Linux-green?style=for-the-badge&logo=Kali)




![Python](https://img.shields.io/badge/Python-3.x-yellow?style=for-the-badge&logo=python)




![License](https://img.shields.io/badge/License-MIT_License-red?style=for-the-badge)




![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge)

</div>

---
**المحتويات:**
- [المميزات](#-المميزات)
- [المنصات المدعومة](#-المنصات-المدعومة)
- [طريقة التثبيت والتشغيل](#-طريقة-التثبيت-والتشغيل)
- [Android — Termux](https://github.com/mmuhacker/Username-Checker/blob/main/README.md#-android--termux)
- [Kali Linux](#-Kali-Linux)
- [طريقة الإستخدام](#-طريقة-الإستخدام)
- [إعدادات Tor](#-إعدادات-Tor)
- [إختصارات مهمة](https://github.com/mmuhacker/Username-Checker/blob/main/README.md#%EF%B8%8F-%D8%A5%D8%AE%D8%AA%D8%B5%D8%A7%D8%B1%D8%A7%D8%AA-%D9%85%D9%87%D9%85%D8%A9)
- [حفظ النتائج](#-حفظ-النتائج)
- [المطور](https://github.com/mmuhacker/Username-Checker/blob/main/README.md#%E2%80%8D-%D8%A7%D9%84%D9%85%D8%B7%D9%88%D8%B1)
---

## ✨ المميزات

- 🌐 فحص **32 منصة** دفعة واحدة
- 🤖 توليد يوزرات تلقائياً بثلاث طرق
- 🔒 دعم **Tor** لتجاوز الحظر
- ⛔ إمكانية إيقاف البحث في أي وقت
- 💾 حفظ النتائج في ملف تلقائياً
- 📋 قراءة يوزرات من ملف txt
- 🌐 فحص يدوي أو تلقائي على كل المنصات دفعة واحدة
- 🔤 دعم كامل للغة العربية في Terminal

---

## 📱 المنصات المدعومة

| الفئة | المنصات |
|-------|---------|
| 📱 التواصل الاجتماعي | Facebook, Instagram, Twitter/X, YouTube, Snapchat, Pinterest, LinkedIn, Reddit, Tumblr, Quora, Medium |
| 💻 تقنية وترفيه | GitHub, Steam, DeviantArt, Twitch |
| 🎥 فيديو وبث | Vimeo, Dailymotion |
| 🎵 موسيقى وصور | SoundCloud, Spotify, Flickr |
| ✈️ تواصل | Telegram |
| 🤖 توليد صور AI | Civitai, NightCafe, Leonardo AI, Tensor.Art, DreamStudio, Dreamlike.art, Dreamstime, Lexica.art, Arthub.ai, Krea.ai, Playground AI |

---

## 🚀 طريقة التثبيت والتشغيل

---

## 📱 Android — Termux

**الخطوة 1 — تثبيت المتطلبات (مرة واحدة فقط)**
```bash
pkg install python tor git curl fontconfig -y
pip install requests pysocks arabic-reshaper python-bidi
```

**الخطوة 2 — تثبيت الخط العربي (مرة واحدة فقط)**
```bash
mkdir -p ~/.termux/fonts && cd ~/.termux/fonts && curl -L "https://fonts.gstatic.com/s/notonaskharabic/v33/RrQ5bpV-9Dd1b1OAGA6M9PkyDuVBePeKNaxcsss0Y7bwvc-VaA.ttf" -o font.ttf && termux-reload-settings
```

> ⚠️ أغلق Termux تماماً وافتحه من جديد بعد تثبيت الخط

**الخطوة 3 — تنزيل الأداة وتشغيلها**
```bash
curl -L "https://raw.githubusercontent.com/mmuhacker/Username-Checker/main/mud.py" -o /sdcard/Download/mud.py
tor &
sleep 5
cd /sdcard/Download
python mud.py
```

**أو كل شيء في أمر واحد (بعد تثبيت الخط)**
```bash
pkg install python tor git curl fontconfig -y && pip install requests pysocks arabic-reshaper python-bidi && curl -L "https://raw.githubusercontent.com/mmuhacker/Username-Checker/main/mud.py" -o /sdcard/Download/mud.py && tor & sleep 5 && cd /sdcard/Download && python mud.py
```

---

### 🐉 Kali Linux

**الخطوة 1 — تثبيت المتطلبات (مرة واحدة فقط)**
```bash
sudo apt install python3 tor curl fonts-noto-core -y
pip3 install requests pysocks arabic-reshaper python-bidi
```

**الخطوة 2 — تنزيل الأداة**
```bash
curl -L "https://raw.githubusercontent.com/mmuhacker/Username-Checker/main/mud.py" -o ~/Downloads/mud.py
```

**الخطوة 3 — تشغيل الأداة**
```bash
sudo service tor start
cd ~/Downloads
python3 mud.py
```

**أو كل شيء في أمر واحد**
```bash
sudo apt install python3 tor curl fonts-noto-core -y && pip3 install requests pysocks arabic-reshaper python-bidi && curl -L "https://raw.githubusercontent.com/mmuhacker/Username-Checker/main/mud.py" -o ~/Downloads/mud.py && sudo service tor start && sleep 5 && cd ~/Downloads && python3 mud.py
```

---

## 📖 طريقة الإستخدام

```
1. اختر المنصة برقمها من القائمة
2. اختر الوضع:
   • ✍️  يدوي  — أدخل يوزر أو عدة يوزرات
   • 🤖 تلقائي — الأداة تولد وتفحص تلقائياً
3. اختر 0 للفحص على كل المنصات:
   • يدوي  — أدخل يوزر واحد يُفحص على 33 منصة
   • تلقائي — توليد يوزرات وفحص كل واحد على 33 منصة
4. اختر 98 لإعدادات Tor
```

---

## 🔒 إعدادات Tor

الأداة تكشف Tor تلقائياً عند التشغيل.
لتفعيله يدوياً اختر **98** من القائمة.

| الحالة | المعنى |
|--------|--------|
| 🟢 مفعّل | الطلبات مشفرة وتجاوز الحظر مفعّل |
| 🔴 معطّل | الاتصال المباشر |

---

## ⌨️ إختصارات مهمة

| الاختصار | الوظيفة |
|----------|---------|
| `Volume↓ + C` (Termux) / `Ctrl+C` (Kali) | إيقاف البحث فوراً |
| `0` | فحص على كل المنصات |
| `98` | إعدادات Tor |
| `-1` | خروج |

---

## 📂 حفظ النتائج

**Termux:**
```
/sdcard/Download/available_[اسم_المنصة].txt
/sdcard/Download/available_[اليوزر].txt
```

**Kali Linux:**
```
~/Downloads/available_[اسم_المنصة].txt
~/Downloads/available_[اليوزر].txt
```

---

<div align="center">

## 👨‍💻 المطور

**Muhannad Daher**

[![GitHub](https://img.shields.io/badge/GitHub-mmuhacker-black?style=for-the-badge&logo=github)](https://github.com/mmuhacker)
[![Contact Us](https://img.shields.io/badge/Contact_Us-black?style=for-the-badge&logo=gmail&logoColor=white)](mailto:madarik.ai.info@gmail.com)

</div>

