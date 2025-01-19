# Max Alarm Volume
In iOS Ringer/Alarm volume are tied to each other. iOS currently has a bug (feature?) where if a Bluetooth device is connected and the user receives a call, it lowers the Ringer Volume by a set amount. If this happens multiple times it will eventually reduce the volume to 0. As a side effect this also reduces the Alarm volume to 0 which is less than desirable (Don't ask me how I know).
This shortcut fixes the issue by raising the volume to 100% with a simple action.

# Setup
1. Import [Max Alarm Volume.shortcut](Max%20Alarm%20Volume.shortcut)
2. Set up an automation to run this shortcut whenever Any Bluetooth Device is disconnected.