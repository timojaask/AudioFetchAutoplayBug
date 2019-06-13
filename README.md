# AudioFetch Autoplay Bug

To reproduce the bug:

1. Run the app on an iOS device connected to WiFi with AudioFetch hardware
2. Tap "getAudioManagerInstance" button
3. Press iPhone Home button to exit to iOS home screen
4. Tap on the app to bring it back from background

Observe AudioFetch SDK automatically starting to play the first channel.
