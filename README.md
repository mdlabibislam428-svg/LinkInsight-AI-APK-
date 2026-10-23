# LinkInsight AI Android app

This Android WebView app opens the LinkInsight AI website:

https://your0ai1is2here.base44.app

## Build an APK

GitHub Actions builds a debug APK automatically after a push to `main`, or on demand from the **Actions** tab using **Build LinkInsight AI APK** → **Run workflow**.

After the workflow succeeds:
1. Open the workflow run.
2. Scroll to **Artifacts**.
3. Download **LinkInsight-AI-debug-APK** and extract the ZIP.
4. Install `app-debug.apk` on your Android phone.

This is a WebView wrapper and requires an internet connection to load the website. The APK is a debug build, not a Play Store release-signed build.
