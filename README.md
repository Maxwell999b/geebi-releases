<div align="center">

# Geebi · جيبي

**Point-of-sale for cafes and restaurants — orders, kitchen, inventory, staff and reports in one app.**
**نظام نقاط بيع للمقاهي والمطاعم — الطلبات والمطبخ والمخزون والموظفين والتقارير في تطبيق واحد.**

[**⬇ Download for Android (APK)**](https://github.com/Maxwell999b/geebi-releases/releases/latest/download/geebi.apk) ·
[Open the web app](https://app.geebi.app) ·
[geebi.app](https://geebi.app/download)

</div>

---

This repository only hosts **downloads of the Geebi apps**. The Geebi source code is private.
هذا المستودع للتحميل فقط، والكود المصدري لجيبي خاص.

## Choose your device

| Device | How to get Geebi |
|---|---|
| **Android phone / tablet** | Download the APK above and install it (steps below). |
| **iPhone / iPad** | Open <https://app.geebi.app> in **Safari** → **Share** → **Add to Home Screen**. |
| **Windows** | Open <https://app.geebi.app> in **Chrome or Edge** → click the **Install** icon in the address bar. |
| **Any browser** | Just open <https://app.geebi.app>. |

> iOS cannot install APK files. On iPhone and iPad, the home-screen web app is the supported way, and it updates by itself.

## Install on Android

1. On your phone, tap **Download for Android (APK)** above and wait for `geebi.apk` to finish downloading.
2. Open the file. If Android says *"For your security, your phone isn't allowed to install unknown apps from this source"*, tap **Settings** and switch on **Allow from this source** for the browser you used. This is asked once.
3. Tap **Install**. If **Play Protect** shows a warning, tap **More details → Install anyway**.
4. Open **Geebi** and sign in with your account.

### Why does Android warn me?
Android shows this notice for **every app installed outside Google Play**. It is not a sign that the file is harmful. The app is signed with Geebi's own key, and you can check the file yourself (see *Verify the download*).

## Updating

- The app shows the latest screens and features automatically whenever you open it. You do **not** need to reinstall for normal updates.
- When a new Android version is released, the app tells you with a banner and a phone notification. Tap **Update now**: the app downloads the new version and Android asks you to confirm the install once. It installs **over** the old one. Your data stays on your account, and you never need to uninstall.
- On older versions (1.1.0 and below) the banner has a download link instead. Download the newest `geebi.apk` and install it over the old one. Once you are on 1.2.0 or later, the in-app **Update now** button is available.
- The first time you update, Android may ask you to allow Geebi to install updates, and to allow notifications. Both are optional but make updating smoother.

## Verify the download

Every release lists the SHA-256 of `geebi.apk` in its notes. To check it:

```powershell
# Windows PowerShell
Get-FileHash .\geebi.apk -Algorithm SHA256
```
```bash
# macOS / Linux
sha256sum geebi.apk
```

The app is signed with a key whose certificate fingerprint (SHA-256) is:

```
AC:E6:78:9C:83:8A:24:EB:29:BE:7F:44:14:59:F2:75:3F:68:97:B7:3E:16:5B:EF:6D:6E:F3:37:D9:D3:CD:28
```

---

## بالعربي

### التحميل
| الجهاز | الطريقة |
|---|---|
| **أندرويد** | حمّل ملف APK من الزر أعلاه ثم ثبّته (الخطوات تحت). |
| **آيفون / آيباد** | افتح <https://app.geebi.app> في **Safari** ← **مشاركة** ← **إضافة إلى الشاشة الرئيسية**. |
| **ويندوز** | افتح <https://app.geebi.app> في **Chrome أو Edge** ← اضغط أيقونة **تثبيت** في شريط العنوان. |

> الآيفون لا يقبل ملفات APK، والطريقة المدعومة عليه هي إضافة التطبيق إلى الشاشة الرئيسية، ويتحدث تلقائياً.

### التثبيت على أندرويد
1. من الهاتف اضغط **Download for Android (APK)** وانتظر اكتمال تحميل `geebi.apk`.
2. افتح الملف. لو ظهرت رسالة *«لا يُسمح بتثبيت تطبيقات غير معروفة من هذا المصدر»* اضغط **الإعدادات** وفعّل **السماح من هذا المصدر** للمتصفح الذي استخدمته (تُطلب مرة واحدة فقط).
3. اضغط **تثبيت**. لو ظهر تحذير **Play Protect** اضغط **مزيد من التفاصيل ← التثبيت على أي حال**.
4. افتح **جيبي** وسجّل الدخول بحسابك.

**لماذا يحذّرني أندرويد؟** هذه الرسالة تظهر مع أي تطبيق يُثبَّت من خارج متجر Google Play، وليست دليلاً على أن الملف ضار. التطبيق موقّع بمفتاح جيبي الخاص ويمكنك التحقق من الملف بنفسك.

### التحديث
- التطبيق يعرض أحدث الشاشات والمزايا تلقائياً عند فتحه، ولا تحتاج لإعادة التثبيت في التحديثات العادية.
- عند صدور نسخة أندرويد جديدة يخبرك التطبيق بشريط تنبيه وإشعار على الهاتف. اضغط **تحديث الآن** فيحمّل التطبيق النسخة الجديدة ويطلب منك أندرويد تأكيد التثبيت مرة واحدة. يثبّت **فوق** النسخة القديمة وبياناتك محفوظة في حسابك، ولا تحتاج لحذف التطبيق.
- في النسخ الأقدم (1.1.0 وما قبلها) يظهر رابط تحميل بدل الزر. حمّل أحدث `geebi.apk` وثبّته فوق القديم. بعد الوصول إلى 1.2.0 أو أحدث يتوفر زر **تحديث الآن** داخل التطبيق.
- في أول تحديث قد يطلب أندرويد السماح لجيبي بتثبيت التحديثات والسماح بالإشعارات، وكلاهما اختياري لكنه يسهّل التحديث.

---

Questions or problems? Contact us through <https://geebi.app/contact>.
© Geebi. All rights reserved.
