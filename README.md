# Goku: Chaldea Brawler — Android fan-game prototype

An offline, standalone Android Studio project based on the user's Son Goku ★★★★ SR Berserker concept.

## Included
- Servant profile with the supplied Level 100 Grail ATK/HP and parameters
- Class skills and all three personal skills
- Tap-to-play training battle with Quick, Arts and Buster command cards
- NP gauge, Critical Star counter, skill buttons and battle log
- Kamehameha Noble Phantasm screen and a simple visual effect
- User-provided Goku art bundled in `app/src/main/assets/goku.png`

## Build and run
1. Install Android Studio (a recent version with Android SDK Platform 35).
2. Open the `GokuFGOAndroid` folder in Android Studio.
3. Let Gradle sync and install any prompted SDK components.
4. Select an Android device or emulator (Android 8.0 / API 26 or later).
5. Press **Run**.

To create an APK in Android Studio: **Build → Build Bundle(s) / APK(s) → Build APK(s)**. The APK will appear under `app/build/outputs/apk/debug/` after a successful build.

## Notes
- This is a source project, not a prebuilt APK. It has not been compiled in this environment.
- Combat values are prototype/demo values, not a full recreation of FGO's damage formula.
- Guts, buffs and skills are represented as lightweight prototype mechanics; this is not connected to the official FGO app or servers.
- This is an unofficial fan-made project. Fate/Grand Order, Dragon Ball and their respective characters/trademarks belong to their rights holders. No affiliation or endorsement is implied.

## Phone-only cloud build option
The `.github/workflows/build.yml` workflow can build a debug APK on GitHub Actions after the project files are uploaded to the root of a GitHub repository. In the repository's Actions tab, choose **Build Goku Android APK** and select **Run workflow**. When the run succeeds, open that run and download the `Goku-Chaldea-Brawler-debug-apk` artifact. GitHub may require an account and Actions to be enabled. This workflow has been added but has not been run or verified here.
