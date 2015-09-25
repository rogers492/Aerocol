1. Save the file main.lua
2. The Simulator will ask if you want to relaunch (it will know the project files were modified)
3. Click yes to run main.lua in the Simulator
4. Then, from the Simulator File-menu, click Build For Android
5. Corona will connect to the server and compile the .apk (Android package) into the CoronaBuilds/Android directory
6. Copy the .apk file from your PC folder to your Apps folder on Google Drive (or any other convenient file store in the cloud)
7. Open Google Drive on your phone and download the .apk
8. When asked, choose install (you must have set permission on the phone to load apps from unknown sources [ie not the Google Play Store])
9. Note the full set of icons Corona expects for an Android app!



The old way was:
6. Connect the phone to the PC via USB
7. Next, run the Android Dev Bridge:
	C:\>adb install -r C:\Users\Paul\Documents\CoronaBuilds\Android\nexBus.apk
8. This will install the app on the phone (so long as you have set permission on the phone to load apps from unknown sources [ie not the Google Play Store])
9. Note the full set of icons Corona expects for an Android app!
10. In adb, the command 'adb devices' can be used to confirm the phone-usb-pc channel is open