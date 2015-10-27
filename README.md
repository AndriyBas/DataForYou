# DataForYou

Enviromental requirements:
To build this project you should have Java, Gradle and Android Studio(optionaly) installed on your computer.
To run an app you should have physical device or emulator/

You can build project with command line or IDE:
For command line build you have to run these commands:
<p>For Unix: <br> $ chmod +x gradlew <br>$ ./gradlew assembleDebug <br> The first command (chmod) adds the execution permission to the Gradle wrapper script and is only necessary the first time you build this project from the command line.</p>
<p>For Windows: <br> > gradlew.bat assembleDebug <br></p>
After you build the project, the output APK for the app module is located in app/build/outputs/apk/<br>
Instructions for installing apk file [on device] (http://developer.android.com/tools/building/building-cmdline.html#RunningOnEmulator) or [emulator] (http://developer.android.com/tools/building/building-cmdline.html#RunningOnDevice)<br>
[Aditional information about build with command line](http://developer.android.com/tools/building/building-cmdline.html)<br>
For building in Android Studio import project into IDE and click "run"(green triangle) then choose device, where you want run app.
[Aditional information about build in Android Studio] (http://developer.android.com/tools/building/building-studio.html)
