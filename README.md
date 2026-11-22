# Tamil Tv Portal (Android TV / TV box)

Streams free, publicly available Tamil channels (news, entertainment, movies, music, devotional, kids) using Media3 ExoPlayer. D-pad and remote friendly.

## Get the APK

**Option A – GitHub (no setup):**
1. Create a new GitHub repository and upload this whole folder.
2. Open the *Actions* tab → *Build APK* → run it.
3. Download `TamilTvPortal-apk` → `app-debug.apk`.

**Option B – Android Studio:**
Open this folder → *Build > Build APK(s)*. Output: `app/build/outputs/apk/debug/app-debug.apk`.

## Install on TV box
- Copy the APK to a pen drive, or use "Downloader" app / `adb install app-debug.apk`.
- Allow "Install unknown apps" for your file manager.

## Remote controls
- Home screen: Channel Up/Down (or Menu / Green) = next category, Red = reload.
- Player: Up / Channel Up = next channel, Down / Channel Down = previous.

## Adding channels
- `app/src/main/assets/sources.txt` – add more M3U playlist URLs.
- `app/src/main/assets/my_channels.m3u` – add individual channels (e.g. a Tiruvallur/TACT local channel, if its operator publishes an official stream).

Dead links are skipped automatically.
