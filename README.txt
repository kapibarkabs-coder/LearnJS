LearnJS — Android Studio project

Application display name: LearnJS
Package ID: com.learnjs.app
Type: offline Android WebView wrapper around the LearnJS lessons.

BUILD LOCALLY:
1. Install Android Studio with Android SDK Platform 35 and JDK 17.
2. Open this folder in Android Studio.
3. Let Gradle sync and install any requested SDK components.
4. Choose Build > Build Bundle(s) / APK(s) > Build APK(s).
5. Debug APK will be under app/build/outputs/apk/debug/app-debug.apk.

BUILD IN THE CLOUD:
1. Upload this project to a GitHub repository.
2. Open the repository's Actions tab and select "Build LearnJS APK".
3. Press "Run workflow" (or push to main).
4. When the workflow finishes, open its run and download the "LearnJS-APK" artifact.
5. Extract the downloaded artifact to get app-debug.apk.

Important: this archive is the source project, not an APK. The current environment
does not have Android SDK / Gradle, so a compiled APK could not be generated here.
