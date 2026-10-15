Device
- Android 7.0 (API 24) or newer.
- Android System WebView. The game runs inside the phone's built-in browser engine (WebView), using WebAssembly. Any WebView updated in the last several years works. If the game shows a black screen or an error, update "Android System WebView" (or Chrome) from the app store.
- Any CPU type (ARM or x86). The APK contains no native code, so it isn't tied to one architecture.
- Performance. A mid-range phone from the last 5 years or so should be fine. I haven't tested it on low-end devices.
- Storage. About 4 MB for the APK, plus about 10 MB for the game files and saves after the first launch.
- It won't run on iPhone or iPad.

Permissions and network
- No permissions. The app doesn't ask for anything, not even internet access.
- Works fully offline. Everything is packed inside the APK.

Installing
- You install the APK file yourself. It's not on Google Play, so you need to allow "Install unknown apps" for whatever opens the file (your file manager or WeChat, for example).
- It's signed with a debug certificate from the PC I built it on. To install a newer version over the old one, I have to build it on that same PC (C:\Users\CD). An APK signed with a different key won't install over this one. You'd have to uninstall the old version first, and that deletes your saves.

Saves
- Saves are stored inside the app's own data. Uninstalling the app or tapping "Clear data" in Android settings deletes them. Updating the app keeps them.

Screen
- Landscape only. The app rotates to landscape on its own; you can flip the phone either way.
