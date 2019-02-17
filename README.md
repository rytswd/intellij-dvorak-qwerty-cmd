# IntelliJ IDEA - Dvorak with QWERTY CMD
This is based on an idea from https://github.com/scoofy/Intellij-IDEA-Dvorak-QwertyCMD-keymap.  
Somehow I couldn't get this to work on my machine, and thus went ahead doing it manually.

## WHAT: Keymap update setting for specific users
This repository updates the IntelliJ IDEA keymap for "Dvorak - QWERTY CMD" users.

## WHY: IntelliJ IDEA does NOT take QWERTY CMD into an account
It seems as if IntelliJ is overriding the key bindings from macOS - and actually causing some serious troubles.

For example,  
> Opening Preferences (`Cmd + ,`) -> Opens the Preferences window -> At the same time, as `,` is where `w` is in Dvorak, it closes the currently open tab as well

## HOW: Use XML mapping or import from jar file
I added two exported settings - one as XML, and one as jar.  

### Jar
The jar version is ready to be imported as is.

1. Download the JAR file
2. Navigate to `File -> Import Settings...` and choose the jar file.
3. Install

### XML
I'm not sure how you would be able to install from Zip file.  
You may be able to open the preference file manually, and replace with the xml input.
