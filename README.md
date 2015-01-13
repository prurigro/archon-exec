# archon-exec #

A wrapper for **ARChon** and **chromeos-apk** to launch _Android APKs_ in a single step

## Dependencies ##

* [ARChon](https://bitbucket.org/vladikoff/archon): Executes converted _ARChon APKs_
* [chrome](http://www.google.com/chrome) or [chromium](https://download-chromium.appspot.com/): Runs **ARChon** inside as an extension
* [chromeos-apk](https://github.com/vladikoff/chromeos-apk): Extracts _Android APKs_ and converts them to _ARChon APKs_

## Configuration ##

Configuration is done by setting the values of the following environment variables:

* `ARCHON_APKROOT`: The directory to extract and install APK files (default: `/tmp/archon`)
* `ARCHON_CONFIG`: The directory to manage config data for each APK (default: `$HOME/.config/archon`)
* `ARCHON_PATH`: The directory containing **ARChon** (default: `/opt/archon`)

## USAGE ##

Simply run `./archon-exec /path/to/file.apk` and the application should start right up!

## CREDITS ##

Written by Kevin MacMartin:

* [GitHub Projects](https://github.com/prurigro)
* [Arch Linux AUR Packages](https://aur.archlinux.org/packages/?SeB=m&K=prurigro)

## LICENSE ##

Released under the [MIT license](http://opensource.org/licenses/MIT).
