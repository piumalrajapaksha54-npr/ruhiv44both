# RUHI MOBILE V44 Android App source

මෙම folder එක Android Studio project source එකයි; දැනටමත් build කළ APK file එකක් නොවේ.

## APK එක build කරන ආකාරය
1. Android Studio (Hedgehog හෝ අලුත්) install කරන්න.
2. `android-app` folder එක Android Studio වල Open කරන්න.
3. Android SDK Platform 35 සහ Android Gradle Plugin අවශ්‍ය components install කිරීමට ඉඩ දෙන්න.
4. Build > Build Bundle(s) / APK(s) > Build APK(s) තෝරන්න.
5. APK එක `android-app/app/build/outputs/apk/debug/app-debug.apk` යටතේ ලැබේ.

App එකේ HTML/CSS/JS assets APK එක තුළ bundle වන නිසා install කළ පසු ඒවා offline load වේ. App data Android app storage තුළ තබාගනී. App uninstall කිරීම හෝ Clear storage කිරීමෙන් local data මැකිය හැක; Backup export එකක් තබාගන්න.
