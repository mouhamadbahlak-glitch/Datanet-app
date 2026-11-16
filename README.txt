Data Net (غلاف WebView للبوابة)
1) Android Studio > Open > اختر مجلد datanet_android > انتظر Gradle Sync.
2) غيّر عنوان البوابة (إن لزم) بالسطر PORTAL_URL داخل app/build.gradle.kts ثم Sync.
3) للتجربة: وصّل الموبايل (USB debugging) أو شغّل محاكي > زر Run.
4) لنسخة التوزيع: Build > Generate Signed App Bundle / APK > APK > أنشئ keystore جديد (احفظه!) > release.
   الملف الناتج: app/release/app-release.apk
