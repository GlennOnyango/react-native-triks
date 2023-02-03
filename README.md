# react-native-tricks
# feel free to add more


opening avd on ubuntu - /home/{your-name}/Android/Sdk/emulator - ./emulator
Listing avd - /home/glenn/Android/Sdk/emulator - [-list-avds]

Debuging

Useful to debug native errors (when the app won't even start)

adb logcat "*:E"

Useful to debug JS code errors

adb logcat "*:S" ReactNative:V ReactNativeJS:V
