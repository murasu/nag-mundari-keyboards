# Nag Mundari Keyboards

Created : 19 Feb 2023 by Muthu Nedumaran

Keyboard layout files for the Nag Mundari script. This script was added to the Unicode Standard 15.0.

## macOS
![macOS keylayout](https://raw.githubusercontent.com/murasu/nag-mundari-keyboards/main/images/macos.png)
![macOS keylayout shifted](https://raw.githubusercontent.com/murasu/nag-mundari-keyboards/main/images/macos-shift.png)
The keyboard layout, created in [Ukelele](https://software.sil.org/ukelele/), was tested to work well on macOS Monterey 12.6.x. It should work on Catalina and Bug Sur as well but it has not been tested. Installing the keyboard on macOS machines is straight forward.

1. Copy the NagMundari.keylayout file to ~/Library/Keyboard Layouts directory or /Library/Keyboard Layouts directory if it's for all users.
2. Logout and login again
3. Add the new keyboard via System Preferences/Keyboard/Input Sources. Nag Mundari will not be in the language list. Look for it in "Others".

## Windows

1. The repo includes the keyboard layout source and the installer binaries. The .klc file was converted from .keylayout made for macOS using: [adobe-type-tools/keyboard-layouts](https://github.com/adobe-type-tools/keyboard-layouts)
2. To install or uninstall, just run setup in the directory Windows/nmundari. This works well on Windows 10 and 11. The installed keyboard will say Oriya US (NagMundari). But the text output will be Nag Mundari.
3. To build the installers from scratch, open the .klc file in MKLC, [Microsoft Keyboard Layout Creator](https://www.microsoft.com/en-us/download/details.aspx?id=102134) and build the binaries. This will create the dlls and setup.exe file.
4. Since MKLC does not include Nag Mundari as a supported script or language, I picked Oriya. 
5. While the keyboard can be used across all applications, Notepad, Wordpad and Word does not handle text in this script very well. I used [BablePad](https://www.babelstone.co.uk/Software/BabelPad.html) to test. This works well in Windows 10 and Windows 11.

![BablePad](https://raw.githubusercontent.com/murasu/nag-mundari-keyboards/main/images/bablepad.png)

