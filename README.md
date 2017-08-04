To get all required jars for stagemonitor-web

```
git clone https://github.com/felixbarny/stagemonitor-get-all-libs.git
cd stagemonitor-get-all-libs
./gradlew copyLibs -PstagemonitorVersion=<version>
```

Replace \<version\> with the stagemonitor version you want to use.  Version numbers can be found [here](https://github.com/stagemonitor/stagemonitor/releases).

All the libs are in the `build` folder

If you are on windows, replace `./gradlew` with `gradlew.bat`
