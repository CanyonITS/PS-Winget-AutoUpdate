# Winget-autoupdate
Scripts to create scheduled tasks to daily update apps as system and notify connected users

## Intallation
Simply download project, unzip, run install.bat as admin.

## Info
### Keep some apps out of Winget-AutoUpdate
You can exclude app to update (for instance, apps you want to keep at a certain version or apps with built in auto-update):
Add the apps' ID you want to disable autoupdate to 'sample-excluded_apps.txt' and rename it to 'excluded_apps.txt'. (File must be in installation folder, or re-run install.bat)
### Default install location
By default, scripts and componants will be placed in ProgramData location (inside Winget-autoupdate folder). You can change this in the install ps1 script.

## Optimization
As I am not originaly a script dev, feel free to give me any advise or optimizations in code. Thanks :ok_hand:
