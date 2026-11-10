WEEKLY SALES REPORTING APP - ANDROID STUDIO RETRY PACKAGE

PLEASE READ FIRST
This is the Android Studio project source for the weekly sales reporting app.
It is not an APK installer. Android Studio must build the APK on your computer.

OPEN THE PROJECT
1. Extract this ZIP to a normal folder on your computer.
2. Open Android Studio.
3. Choose File > Open.
4. Select the extracted WeeklySalesReportingApp_Retry folder (the folder containing settings.gradle).
5. If Android Studio asks to trust the project, choose Trust.
6. Set Gradle JDK to Android Studio's Embedded JDK (JDK 17).
7. Install Android SDK Platform 35 in Tools > SDK Manager if it is not installed.
8. Allow Android Studio to sync and download the Gradle 8.7 distribution and Android Gradle Plugin. Internet is required.
9. When sync finishes, connect your Android phone with USB debugging enabled and press the green Run button.

IF ANDROID STUDIO ASKS ABOUT GRADLE
This package includes the Gradle wrapper configuration, but not the wrapper launcher JAR/scripts.
If Android Studio cannot start the sync automatically, choose the Gradle distribution setting in
Settings > Build, Execution, Deployment > Build Tools > Gradle and use the IDE's configured Gradle
installation/distribution, or send a screenshot of the exact message so the project can be adjusted.

APP FEATURES
- Representative name saved on that device
- Weekly activity reporting
- Date, client, site, invoice/order number, quote number, comments, next action,
  follow-up due date and status
- Weekly and monthly Excel exports
- CSV export and JSON backup/restore
- App HTML download for GitHub

IMPORTANT
- This first version stores reports on each phone. It does not sync reports to management or other reps.
- Excel export needs internet access because its spreadsheet library loads from jsDelivr.
- The app project has been packaged and its ZIP contents checked, but it has NOT been built
  or tested on your particular computer/device. Do not treat it as a verified APK yet.


LATEST UPDATE — MANAGE REPRESENTATIVE NAMES
Open Rep settings, then Manage representative names. Choose Remove name beside a representative and confirm. This removes the name from the active representative list and clears it as the phone default if it was selected. Previously saved activities and reports are NOT deleted. If the same name is entered and saved again later, it is added back to the active list.
