## Changelog:

### v9: - `To be released`
 - New build system targets and tweaks
 - Added setting to toggle automatic refresh of the app grid

### v8: `- 2021-06-17`
 - Added donation button to README and preferences
 - Added changelog
 - Fixed folders not automatically reordering when their names are changed (GNOME 40)
 - Fixed error when disconnecting from connected signals
 - Fixed incorrect position in grid for some folders (GNOME 40)
 - Improved repository structure
 - Only send log messages when debugging is enabled (In `metadata.json`)
 - Miscellaneous code fixes and improvements

### v7: `- 2021-06-11`
 - Added settings to choose position of folders (Alphabetical, start or end)
 - Suport instant redisplaying of the grid order on GNOME 3.38
 - General code improvements

### v6: `- 2021-06-03`
 - Added settings menu
 - Added setting to toggle folder contents reordering
 - Added more files to make clean target
 - Added shellcheck GitHub CI runner
 - Fixed apps not reordering when favourite apps change
 - Replaced script to compile locales
 - Updated documentation
 - Increased consistency of code styling

### v5: `- 2021-05-29`
 - Added translation support
 - Added new build system
 - Added German translation - [Philipp Kiemle](https://github.com/daPhipz)
 - Fixed folder contents not being reordered
 - Fixed a typo in a log message
 - Updated documentation
 - General code improvements

### v4: `- 2021-05-20`
 - Updated `README.md`
 - Reorder the grid when folders are created or destroyed

### v3: `- 2021-05-16`
 - Increased code consistency
 - Updated `README.md`
 - Updated the showcase screenshot
 - Added GNOME 40 support
 - Check gsettings key is writable before writing to it
 - Added support for instant redisplaying of the grid order

### v2: `- 2021-05-10`
 - App grid is now initially reordered when the extension is enabled

### v1: `- 2021-05-10`
 - Initial release