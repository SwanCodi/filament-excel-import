# Filament Excel Import

استيراد ملفات Excel في Filament  
Excel Import for Filament

---

## 🇸🇦 الوصف | Description

**Filament Excel Import** هي حزمة Laravel تتيح لك استيراد ملفات Excel بسهولة داخل **Filament Admin Panel**، مع دعم كامل للغة العربية وتحسينات تقنية.

**Filament Excel Import** is a Laravel package that allows you to easily import Excel files into the **Filament Admin Panel**, with full Arabic language support and technical enhancements.

---

## 🧠 فكرة الحزمة | Package Idea

تم تعديل هذه الحزمة وبناؤها اعتمادًا على مشروع مفتوح المصدر، مع إضافة دعم اللغة العربية وتحسين تجربة الاستخدام.

This package is based on an existing open-source project and has been extended with Arabic language support and usability improvements.

---

## ✨ المميزات | Features

- استيراد ملفات Excel (`.xlsx`, `.xls`, `.csv`)
- تكامل كامل مع Filament v3
- دعم الملفات الكبيرة
- تخصيص الأعمدة والتحقق من البيانات
- منطق استيراد مخصص
- ترجمة عربية مدمجة
- واجهة بسيطة ونظيفة

---

- Import Excel files (`.xlsx`, `.xls`, `.csv`)
- Seamless integration with Filament v3
- Large file support
- Column mapping and validation
- Custom import logic
- Built-in Arabic translations
- Clean and simple UI

---

## ⚙️ المتطلبات | Requirements

| المتطلب | Requirement | الإصدار | Version |
|-------|------------|--------|---------|
| PHP | PHP | ^8.1 | ^8.1 |
| Laravel | Laravel | ^10 \| ^11 | ^10 \| ^11 |
| Filament | Filament | ^3 | ^3 |
| Excel | maatwebsite/excel | ^3.1 | ^3.1 |

---

## 📦 التثبيت | Installation

### 🔹 الطريقة 1: التثبيت من Git (قبل النشر على Packagist)  
### Method 1: Install from Git (Before Packagist)

#### 1️⃣ إضافة المستودع  
Add the repository to your project `composer.json`

```json
{
  "repositories": [
    {
      "type": "vcs",
      "url": "https://github.com/YOUR_USERNAME/filament-excel-import"
    }
  ]
}
