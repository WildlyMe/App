# Description
Be gently but clearly reminded to take breaks during work.

# Development
Run all commands from the project root

### Setup
```sh
npm install
```

### Run tests
```sh
npx jest
```

### Run on phone/emulator
Start "Mono" terminal
```sh
npx react-native start
```

Run on phone
```sh
npx react-native run-android
```

##### Reload
Either press "r" in "Mono" terminal, or
```sh
adb shell input text "RR"
```

### Install on phone
```sh
npx react-native run-android --variant=release
```