# quiz_app

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.


First Flutter Project created and when running on Emulator or Mobile Deivce is showing errors:
Runnning Time Console showin below Error:

---------------------------------------------------------

Launching lib\main.dart on Android SDK built for x86 in debug mode...
Running Gradle task 'assembleDebug'...
Warning: Mapping new ns http://schemas.android.com/repository/android/common/02 to old ns http://schemas.android.com/repository/android/common/01
Warning: Mapping new ns http://schemas.android.com/repository/android/generic/02 to old ns http://schemas.android.com/repository/android/generic/01
Warning: Mapping new ns http://schemas.android.com/sdk/android/repo/addon2/02 to old ns http://schemas.android.com/sdk/android/repo/addon2/01
Warning: Mapping new ns http://schemas.android.com/sdk/android/repo/repository2/02 to old ns http://schemas.android.com/sdk/android/repo/repository2/01
Warning: Mapping new ns http://schemas.android.com/sdk/android/repo/sys-img2/02 to old ns http://schemas.android.com/sdk/android/repo/sys-img2/01
Parameter format not correct -

FAILURE: Build failed with an exception.

* What went wrong:
Execution failed for task ':app:stripDebugDebugSymbols'.
> NDK at C:\Users\Andy\AppData\Local\Android\Sdk\ndk\21.1.6352462 did not have a source.properties file

* Try:
Run with --stacktrace option to get the stack trace. Run with --info or --debug option to get more log output. Run with --scan to get full insights.

* Get more help at https://help.gradle.org

BUILD FAILED in 11s
Exception: Gradle task assembleDebug failed with exit code 1
---------------------------------------------------------------------------
Above mentioned erro if you want to solve this then open   
![Screenshot (768)](https://user-images.githubusercontent.com/47913444/191756499-c2a153f3-1793-4950-b99e-5cb4f321c6b0.png)
then change few code like below given

![Screenshot (769)](https://user-images.githubusercontent.com/47913444/191756702-23ad92e7-3308-4519-9ea0-6b839e08d546.png)

besides this, 
![Screenshot (770)](https://user-images.githubusercontent.com/47913444/191756827-3b112872-a2ee-4f04-91da-6754db871cdb.png)
then change few code like below given

![Screenshot (771)](https://user-images.githubusercontent.com/47913444/191757117-8e3531a6-387a-46fa-bc51-ed79cada2d07.png)

Then I have tryied to run Flutter project and it is completely working. Now this error is sucessfully resolve. 


