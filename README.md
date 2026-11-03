# ULTRAS GREEN GHOST

نسخة بدون أغاني أو ملفات صوتية أو أخبار تجريبية/وهمية.

- تم حذف ملف الأغنية من assets.
- تم حذف مشغل الصوت وأزرار تشغيل/إيقاف الأغاني.
- تم حذف اعتماد expo-av من المشروع.
- لا يحتوي هذا الإصدار على قسم أخبار؛ لن تظهر أخبار مختلقة على أنها حقيقية.

## التشغيل
```bash
npm install
npx expo start
```

## بناء APK
يتم البناء عبر GitHub Actions باستخدام ملف workflow المرفق في مجلد `.github/workflows`.


## App and notification icons
- `assets/icon.png` is the supplied OCK / Green Ghost badge used as the Android app icon.
- `assets/notification-icon.png` is the monochrome Android small-notification icon.
- Android displays the small icon only when the app posts a notification; an icon cannot stay in the status bar permanently without an ongoing notification and the required user permission.
