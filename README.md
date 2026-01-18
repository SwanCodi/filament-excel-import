Filament Excel Import

استيراد ملفات Excel في Filament
Excel Import for Filament Admin Panel

🇸🇦 الوصف | Description

Filament Excel Import هي حزمة Laravel تتيح استيراد ملفات Excel بسهولة ومرونة داخل Filament Admin Panel، مع دعم كامل للغة العربية وتحسينات على تجربة الاستخدام والأداء.

Filament Excel Import is a Laravel package that allows you to easily import Excel files into the Filament Admin Panel, with full Arabic language support and enhanced usability.

🧠 فكرة الحزمة | Package Idea

تم تطوير هذه الحزمة اعتمادًا على مشروع مفتوح المصدر، مع:

إضافة دعم اللغة العربية بشكل كامل

تحسين واجهة المستخدم

تبسيط تجربة الاستيراد داخل Filament

This package is based on an existing open-source project and has been extended with Arabic language support and UX improvements.

✨ المميزات | Features

📥 استيراد ملفات Excel (.xlsx, .xls, .csv)

⚡ تكامل كامل مع Filament

🧠 دعم منطق استيراد مخصص

🧾 تخصيص الأعمدة والتحقق من صحة البيانات

📊 دعم الملفات الكبيرة

🌍 ترجمة عربية مدمجة

🎨 واجهة بسيطة ونظيفة

⚙️ المتطلبات | Requirements
Requirement	Version
PHP	^8.1
Laravel	^10 | ^11
Filament	^3
maatwebsite/excel	^3.1
📦 التثبيت | Installation
🔹 الطريقة 1: التثبيت من GitHub (قبل النشر على Packagist)
1️⃣ إضافة المستودع إلى composer.json
{
  "repositories": [
    {
      "type": "vcs",
      "url": "https://github.com/SwanCodi/filament-excel-import"
    }
  ]
}

2️⃣ تثبيت الحزمة
composer require swancodi/filament-excel-import

🔹 الطريقة 2: استخدام الحزمة الأصلية

في حال رغبتك باستخدام الحزمة الأصلية بدون التعديلات العربية:

composer require eightynine/filament-excel-import


🔗 المستودع الأصلي:
https://github.com/eighty9nine/filament-excel-import

🧩 التهيئة | Configuration

لا تتطلب الحزمة أي إعدادات إضافية.
تأكد فقط من تثبيت:

Filament

maatwebsite/excel

(سيتم إضافة ملف إعدادات اختياري في الإصدارات القادمة)

🚀 طريقة الاستخدام | Usage
مثال داخل Resource أو Page في Filament
use SwanCodi\FilamentExcelImport\Actions\ExcelImportAction;

ExcelImportAction::make()
    ->label('استيراد ملف Excel')
    ->validateUsing([
        'name' => 'required|string',
        'email' => 'required|email',
    ]);

🌍 الترجمة | Localization

🇸🇦 العربية (افتراضي)

🇬🇧 الإنجليزية

تتبع الحزمة لغة التطبيق في Laravel / Filament تلقائيًا:

'app.locale' => 'ar',

📜 الترخيص | License

هذه الحزمة مبنية على مشروع مفتوح المصدر:

Original Author: EightyNine

Extended & Arabic Support: SwanCodi

تخضع الحزمة لرخصة MIT License.

🤝 المساهمة | Contributing

نرحّب بجميع المساهمات، بما في ذلك:

تحسين الأداء

إضافة ميزات جديدة

تحسين الترجمة العربية

كتابة اختبارات

يرجى إرسال Pull Request أو فتح Issue.

⭐ الدعم | Support

إذا أعجبتك الحزمة:

⭐ ضع Star على GitHub

🐞 أبلغ عن أي مشكلة

💡 اقترح تحسينات

🧑‍💻 المطوّر | Author

SwanCodi
Laravel & Filament Developer
Arabic Open-Source Contributor
