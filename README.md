# windowsKeyboardLayout
How to remove Afrikaans keyboard layout (afr)

If you have the same problem as me, follow this path

First go to Registry Editor (search in Windows search bar or press win+R and type "regedit")

Go to this path "Computer\HKEY_USERS\.DEFAULT\Keyboard Layout\Preload"

And delete `00000436`

And finally go to "Computer\HKEY_USERS\.DEFAULT\Keyboard Layout\Substitutes" and press F2, change `00000436` to `00000409` and press enter

Restart your computer and boom!!! AFR is removed
