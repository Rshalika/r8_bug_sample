# r8_bug_sample

clone and run `gradlew assembleRelease`

Android studio will not open it so use command line `gradlew`

Don't forget to set `ANDROID_SDK_ROOT` environmental variable.

`gradlew assembleDebug` should complete successfully and  
`gradlew assembleRelease` should give R8: `NullPointerException during IR Conversion` error


