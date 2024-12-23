# MPV android build

## prerequisites

- [Android NDK](https://developer.android.com/ndk)

    ```text
    Android NDK: 26.3.11579264
    ```

- [Android SDK](https://developer.android.com/studio)

    ```text
    Android SDK Tools: 36-rc3
    ```

- [Android Studio](https://developer.android.com/studio)

    ```text
    Android Studio Ladybug | 2024.2.1 Patch 3
    Build #AI-242.23339.11.2421.12700392, built on November 23, 2024
    Runtime version: 21.0.3+-79915917-b509.11 aarch64
    VM: OpenJDK 64-Bit Server VM by JetBrains s.r.o.
    Toolkit: sun.∏awt.macosx.LWCToolkit
    macOS 13.0.1
    GC: G1 Young Generation, G1 Concurrent GC, G1 Old Generation
    Memory: 2048M
    Cores: 8
    Metal Rendering is ON
    Registry:
    ide.experimental.ui=true
    i18n.locale=
    ```

- [CMake](https://cmake.org/)

    ```text
    cmake version 3.22.1
    ```

- [Ninja](https://ninja-build.org/)
- [Git](https://git-scm.com/)
- [Python](https://www.python.org/)
- [Java](https://www.java.com/)
- [Gradle](https://gradle.org/)

    ```text
    gradle version 8.6
    ```

## build

```bash
git clone git://github.com/hhool/MPV-android.git
cd MPV-android
git checkout dev_2024_11_16
gradle build
```

## License

MPV-android is released under the [GPLv3](https://www.gnu.org/licenses/gpl-3.0.html) license.

