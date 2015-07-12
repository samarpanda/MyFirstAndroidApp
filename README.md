## Setting up native android app

Install dependencies and project setup

```shell
./gradlew assembleDebug
```

### Deploy app in device

Use `adb` tool to install app in device. Connect device using usb with debugging enabled.

```shell
## cd to application root directory
adb install app/build/outputs/apk/app-debug.apk
```

For more details follow [https://developer.android.com/training/basics/firstapp/running-app.html](https://developer.android.com/training/basics/firstapp/running-app.html)
