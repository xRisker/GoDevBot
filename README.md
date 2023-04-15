<div align="center">

halfbot-example

<br>

![](https://img.shields.io/npm/v/@disqada/halfbot.svg?maxAge=3600)
![](https://img.shields.io/npm/dt/@disqada/halfbot.svg?maxAge=3600)

</div>

# الترجمات

<div align="right">

[العربية](README.md) | [English](README.en.md)

</div>

<br>

---

# عن المشروع

قالب جاهز لكود بوت دسكورد بإستخدام أداة halfbot

<br>
<br>

# قبل التشغيل

## البيئة

يوجد داخل المشروع ملف اسمه `useme.env` قم بتغيير إسمه وإزالة `useme`

داخل الملف ستجد السطر التالي

```
TOKEN=PUT_YOUR_TOKEN_HERE
```

قم بإستبدال `PUT_YOUR_TOKEN_HERE` بتوكن البوت الخاص بك دون وضعه داخل علامات تنصيص ودون ترك أي مسافات

⚠️⚠️ لا تقم بمشاركة التوكن مع أي أحد ⚠️⚠️

<br>

## الإعداد

لتحميل جميع البكجات المطلوبة قم بتشغيل الأمر التالي

```
npm run setup
```

<br>

## البرمجة

يمكنك الآن البدء بتعديل بيانات الملفات في المسار التالي

```
bot/config/
```

وإضافة وظائف إضافية داخل المجلد الصحيح في المسار التالي

```
bot/modules/
```

<br>

# التشغيل

كل ما تبقى الآن هو تشغيل البوت وتجربته، والذي ستقوم به من خلال تشغيل الأمر التالي

```
npm run start
```

أو يمكنك إستخدام الأمر التالي لجعل البوت يعيد الشتغيل بشكل تلقائي بعد كل تعديل وحفظ على الكود

```
npm run watch
```
