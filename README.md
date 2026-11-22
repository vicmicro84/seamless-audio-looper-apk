# Seamless Audio Looper APK

Client-side seamless loop detector + 1-hour MP3 exporter, packaged as an Android WebView app via Capacitor.

## How to get the APK

1. Go to the **Actions** tab of this repository.
2. Select **Build Android APK** workflow.
3. Click **Run workflow** (or wait for the push trigger).
4. When the run finishes (green), download the **seamless-audio-looper-debug-apk** artifact.
5. Unzip and install the `.apk` on your Android device (allow unknown sources).

The APK is a debug build. It runs the exact same web tool you had, inside a full-screen WebView. Analysis speed is the same as the browser version (already optimized with adaptive search).

**Note:** The LAME encoder is loaded from CDN, so the device needs internet the first time the export runs. Everything else is local.

## Source

The web app lives in `www/index.html`.
