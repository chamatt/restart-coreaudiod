# restart-coreaudiod
A simple packaged mac app with the single purpose of running `sudo pkill coreaudiod` with TouchID support. For my fellow compadres who also spilled wine on their brand new macbook while playing Among Us. 

# Instructions

1. Download/Clone the repository
2. Run `chmod 755 ./sudo-via-touch-id.sh` inside the download folder. This will allow you to active sudo via TouchID.
3. Move the 'RestartCoreAudioD' app to your applications folder.
4. (Optional) Drag the app from the application folder to your dock for easy access.



Next time your audio fails, just run the app, scan your finger, and enjoy that sweet audio back again!

# Troubleshoot

The first time you open the app, it won't allow you to run due to it being from an unidentified developer. To solve that, go to your `Applications` folder, `right click` the app, then click `open`.

If it still doesn't allow you to run, go to your `System Preferences` -> `Security & Privacy` -> check if it's blocked there and click `Open Anyway`.


# Credits:

1. Sudo via TouchID: [tjluoma/sudo-via-touch-id](https://github.com/tjluoma/sudo-via-touch-id)
2. App packaging: [Platypus - Create Mac apps from command line scripts](https://sveinbjorn.org/platypus)
3. App Icon: https://icon-icons.com/icon/audio-card/16123 (CC Attribution-NonCommercial-ShareAlike)
