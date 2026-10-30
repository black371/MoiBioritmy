МОИ БИОРИТМЫ — Android проект v2.0

Это исходный Android Studio проект (НЕ готовый APK).

Сборка:
1. Откройте папку MoiBioritmy_Android_v2 в Android Studio.
2. Дождитесь загрузки Android SDK 35 и Gradle (AGP 8.7.3, Java 17).
3. Build > Build Bundle(s) / APK(s) > Build APK(s).
4. Установите app/build/outputs/apk/debug/app-debug.apk на Android.

Приложение работает автономно, без интернет-разрешений. Данные хранятся в WebView localStorage на устройстве. Резервные копии импортируются через выбор файла. Экспорт JSON в этой сборке требует доработки нативного Android Download bridge: HTML-ссылка на Blob может не скачиваться в WebView. Перед обновлением браузерной версии сделайте резервную копию: хранилища браузера и Android-приложения разделены. Сборка использует один и тот же applicationId для последующих обновлений.

Для сборки нужен Android Studio/SDK и доступ к Gradle-зависимостям. В текущей среде Android SDK отсутствует, APK здесь не собран и не протестирован на устройстве.
