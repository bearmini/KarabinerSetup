1. Install Karabiner (former KeyRemap4MacBook)

2. Install Seil (former PCKeyboardHack) (to handle Caps Lock key)

3. System Preferences \> Keyboard \> Modifier Keys

    * Caps Lock Key : No Action  \<\<\< change this
    * Control Key   : Control
    * Option  Key   : Option
    * Command Key   : Command

4. Launchpad or Finder's Application folder \> Seil

    *  Check 'Change Caps Lock' and change the keycode to 59 (Control_L)
    *  Check 'Change Command_L' and change the keycode to 54 (Command_R)
    *  Check 'Change Control_L' and change the keycode to 58 (Option_L)
    *  Check 'Change Option_L'  and change the keycode to 55 (Command_L)

5. Replace the private.xml file in ~/Library/Application Support/Karabiner with the file in this repository.

6. Start Karabiner app from Launchpad or the status bar

    * Open 'Change Key'
    * Push 'Reload XML' button
    * Check all remappings you want

