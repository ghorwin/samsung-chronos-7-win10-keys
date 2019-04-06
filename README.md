# Special key support for Samsung Chronos 7 notebooks on Windows 10

Unfortunately, SAMSUNG did stop its chronos laptop series and does not provide updated drivers for Windows 10.

Some of the special keyboard keys still work with the Windows 10 built-in drivers:
* sound mute/unmute
* sound volume

Unfortunately, the most important special keys do not work:
* brightness adjustment
* CD eject

This repository contains an AutoHotkey script that (re-)adds support for these keys.

Simply install autohotkey, download the file `SamsungChronos7KeyFilterKomplett.ahk` to
some directory on your computer and create an auto-start shortcut to autohotkey with
the script as argument, for example:

`C:\ProgramData\chocolatey\bin\AutoHotkey.exe C:\AutoHotkeyScripts\SamsungChronos7KeyFilterKomplett.ahk`

Once loaded, the script will add support for the three keys mentioned above.

## Credits

The scripts relies on the functionality from https://github.com/qwerty12/AutoHotkeyScripts/tree/master/LaptopBrightnessSetter whose author has adapted code from https://github.com/YashMaster/Tweaky. Thanks guys!
