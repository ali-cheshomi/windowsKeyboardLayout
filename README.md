### windowsKeyboardLayout
#How to remove Afrikaans keyboard layout (afr)

If you have the same problem as me, follow this path

First go to Registry Editor (search in Windows search bar or press win+R and type "regedit")

Go to this path "Computer\HKEY_USERS\.DEFAULT\Keyboard Layout\Preload"

And delete `00000436`

And finally go to "Computer\HKEY_USERS\.DEFAULT\Keyboard Layout\Substitutes" and press F2, change `00000436` to `00000409` and press enter

Restart your computer and boom!!! AFR is removed

**This worked for me, but I don't know about you.**

#If you still have problems, check these sites

>[superuser.com](https://superuser.com/questions/1846837/why-is-afrikaans-keyboard-randomly-installed-on-windows-11)
>[reddit](https://www.reddit.com/r/techsupport/comments/1bsbosk/afrikaans_keyboard_keep_appearing_and_i_cant/)
