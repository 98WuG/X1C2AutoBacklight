# Automatic keyboard backlight

C program taken from [the Arch Linux Wiki](https://wiki.archlinux.org/index.php/Lenovo_ThinkPad_X1_Carbon_(Gen_2)#Automatically_turn_on_backlight_when_typing) to automatically enable keyboard backlighting when the user starts typing.

Added a bash script to change backlight brightness on the fly, as well as restart the systemd service.

    Argument (case-insensitive) should be given as follows:
        Off - Disable backlighting
        Med - Enable medium brightness
        Max - Enable maximum brightness

This has only been tested in the Thinkpad X1 Carbon Gen 2. For more information about how to install, please visit [the Arch Linux Wiki](https://wiki.archlinux.org/index.php/Lenovo_ThinkPad_X1_Carbon_(Gen_2)#Automatically_turn_on_backlight_when_typing).
