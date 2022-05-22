# Development
Run all commands from the **project root**.

### Setup
```sh
npm install
```

### Run tests
```sh
npx jest
```

### Run app on device/emulator
##### Start "Mono" terminal
```sh
npx react-native start
```

##### Run on phone
```sh
npx react-native run-android
```

### Reload app on device/emulator
Either press "r" in "Mono" terminal, or
```sh
adb shell input text "RR"
```

### Install on phone
```sh
npx react-native run-android --variant=release
```