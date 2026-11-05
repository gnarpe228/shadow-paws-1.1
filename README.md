# Shadow Paws for Android

The whole Shadow Paws game as an Android app: every feature of the web version, plus
- mobile controls on by default, full screen, the screen stays on while you play
- the phone's back button closes menus and pauses
- "Save to phone" for photos (Pictures/Shadow Paws) and match recordings (Movies/Shadow Paws)
- inventory export saves to Download/Shadow Paws; import opens your file picker
- multiplayer between phones over the internet (room ID, ready check, chat, locator bar)

## Build
Open this folder in Android Studio, wait for the sync, then in the Terminal panel run

    .\gradlew.bat assembleDebug

The APK is `app/build/outputs/apk/debug/app-debug.apk`. The first build downloads three.js and PeerJS into the app (needs internet once).

`tools/make_android_html.py` turns a newer web version of the game into `app/src/main/assets/index.html`.
