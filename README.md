This repo is built on top of [tanujnotes/Olauncher](https://github.com/tanujnotes/Olauncher)

This launcher is particularly built for encountering my personal distractions. If you are using it for your personal use, add app package names to the `FOCUS_APPS_LIST` and `NOT_REQUIRED_APPS_LIST` in the `app/src/main/java/app/olauncher/Utils/Constants.kt` file.

## Changes include:
- The sorting/filtering logic is enhanced to sort apps based on usage frequency
- Added focus time, which can only be changed by changing the source code
- Apps listed in `NOT_REQUIRED_APPS_LIST` will not be shown in the app drawer
- Moved to kts DSL for gradle build files
- Removed internet permissions for the app
- Using gradle 8.13.1 (because why not)

Will add a more strict rules as and when I come across more distractions.

## Few more todos in mind:
- Remove the unwanted change wallpaper part
