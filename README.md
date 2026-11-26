# Last Zone

لعبة باتل رويال أوفلاين. / Offline battle royale for Android.

## الطريقة (من غير أي برامج)
1. ارفع كل محتويات الفولدر ده في ريبو جديد على GitHub (فرع main).
2. افتح تبويب Actions، وهتلاقي Build APK بيشتغل لوحده (٣-٥ دقايق). لو مشتغلش اضغط Run workflow.
3. بعدها روح Releases ونزّل ملف last-zone.apk على الموبايل وثبّته (فعّل "التثبيت من مصادر غير معروفة").

## Build locally
Android SDK 33 + Gradle 7.x + JDK 11/17: `gradle assembleRelease` -> app/build/outputs/apk/release/app-release.apk
