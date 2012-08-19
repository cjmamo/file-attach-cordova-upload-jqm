To run the example:

1. Replace "http://PutYourServerURL" in index.html with your server URL

2. Install Maven, open your console and enter the following command in the project root directory:

mvn package android:emulator-start android:deploy android:run -Dandroid.emulator.avd="[AVD name]" -Dandroid.emulator.wait="[Wait time]" -Dandroid.sdk.path="[Android SDK path]"