# Filament Excel Import

استيراد ملفات Excel في Filament  
Excel Import for Filament Admin Panel

---

🇸🇦 الوصف | Description

**Filament Excel Import** هي حزمة Laravel تتيح استيراد ملفات Excel بسهولة ومرونة داخل **Filament Admin Panel**.  
تم بناء هذه الحزمة بالاعتماد على مشروع مفتوح المصدر موجود مسبقًا، وقد قمت بإضافة **الترجمة العربية وتحسين تجربة الاستخدام** فقط، دون تعديل جوهري على الكود الأصلي.

**Filament Excel Import** is a Laravel package that allows you to easily import Excel files into the **Filament Admin Panel**.  
This package is based on an existing open-source project, and I have added **Arabic translations and usability enhancements** only, without changing the core functionality.


---

## 🧠 فكرة الحزمة | Package Idea

تم تطوير هذه الحزمة اعتمادًا على مشروع مفتوح المصدر، مع:

- إضافة دعم اللغة العربية بشكل كامل
- تحسين واجهة المستخدم
- تبسيط تجربة الاستيراد داخل Filament

This package is based on an existing open-source project and has been extended with Arabic language support and UX improvements.

---

## ✨ المميزات | Features

- 📥 استيراد ملفات Excel (`.xlsx`, `.xls`, `.csv`)
- ⚡ تكامل كامل مع Filament
- 🧠 دعم منطق استيراد مخصص
- 🧾 تخصيص الأعمدة والتحقق من صحة البيانات
- 📊 دعم الملفات الكبيرة
- 🌍 ترجمة عربية مدمجة
- 🎨 واجهة بسيطة ونظيفة

---

## ⚙️ المتطلبات | Requirements

| Requirement | Version |
|------------|---------|
| PHP | ^8.1 |
| Laravel | ^10 \| ^11 |
| Filament | ^3 |
| maatwebsite/excel | ^3.1 |

---

## 📦 التثبيت | Installation

### 🔹 الطريقة 1: التثبيت من GitHub

#### 1️⃣ إضافة المستودع إلى `composer.json`

```json
{
  "repositories": [
    {
      "type": "vcs",
      "url": "https://github.com/SwanCodi/filament-excel-import"
    }
  ]
}
```
### الطريقة 2: استخدام الحزمة الأصلية | Method 2: Using the Original Package

في حال رغبتك باستخدام الحزمة الأصلية بدون التعديلات العربية:

```bash
composer require eightynine/filament-excel-import
```
