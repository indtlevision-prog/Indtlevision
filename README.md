# Indtlevision Live TV — Android starter project

This is an Android Studio starter project with a traditional channel-number guide and category home screen (News, National TV, Entertainment, Movies, Sports, Devotional, Regional). It is **not a finished APK** and its sample channel entries do not contain working stream URLs.

## Open and build
1. Install Android Studio on a computer.
2. Open this `IndtlevisionLiveTV` folder as a project.
3. Allow Gradle sync and install the Android SDK for API 35 if prompted.
4. Add verified, official/authorized stream URLs in `app/src/main/java/com/indtlevision/livetv/MainActivity.kt` to each `Channel` entry.
5. Run on an Android device for testing. Use **Build > Build Bundle(s) / APK(s) > Build APK(s)** to create an APK.

## Before release
- Replace sample listings with channels whose owners/platforms permit in-app playback or redistribution.
- Check branding, logos, territories, ads, privacy policy, and Google Play policies.
- Test playback, network failures, and device compatibility.
- For Play Store, generate a signed Android App Bundle (AAB) and publish through a Google Play developer account.

No private TV channel streams, credentials, or broadcast rights are included in this project.
