# mac-config
Some of the miscellaneous configuration files I use on my work MacBook.

This repo contains the following config files:

* [Karabiner key mapping configuration](karabiner/)

  I have a lot of muscle memory from using Windows and Linux OSs and keyboards, and this makes it a lot easier.
  
  Although I previously remapped some of the modifer keys using the native MacOS Preferences interface, I now have implemented almost everything in my Karabiner configuration.
  
  * On my **Windows keyboard**, I have the modifier keys (<kbd>Ctrl</kbd>&nbsp;<kbd>⊞ Win</kbd>&nbsp;<kbd>Alt</kbd>) remapped as the following:
    
    | Physical keyboard key | Mapped to MacOS... |
    | -----------|------------ |
    | <kbd>Ctrl</kbd> | <kbd>⌘ Command</kbd> |
    | <kbd>⊞ Win</kbd> | <kbd>⌥ Option</kbd> |
    | <kbd>Alt</kbd> | <kbd>^ Control</kbd> |
    
  * On the **built-in MacBook keyboard**, I have the modifier keys (<kbd>fn</kbd>&nbsp;<kbd>^ Control</kbd>&nbsp;<kbd>⌥ Option</kbd>&nbsp;<kbd>⌘ Command</kbd>) remapped as the following:
    
    | Physical keyboard key | Mapped to MacOS... |
    | -----------|------------ |
    | <kbd>fn</kbd> | <kbd>⌘ Command</kbd> |
    | <kbd>^ Control</kbd> | <kbd>fn</kbd> |
    | <kbd>⌥ Option</kbd> | <kbd>⌥ Option</kbd> |
    | <kbd>⌘ Command</kbd> | <kbd>^ Control</kbd> |
    
  I also have a few key extra combination shortcuts that do special things. For example, <kbd>⌥ Option(mapped)</kbd>+<kbd>Tab</kbd> opens MacOS Mission Control, and a single press on <kbd>⌥ Option(mapped)</kbd> is mapped to the keyboard shortcut to open [Alfred](https://www.alfredapp.com/).
  
  
* [MacOS key bindings for text navigation](macoskeybindings/macoskeybindings.md)
  
  In addition to the above Karabiner settings to change keys, I also have changed some of the default MacOS keybindings to make keyboard text navigation behave more like Windows.
  
  This includes changing the behaviour of the <kbd>Home</kbd> and <kbd>End</kbd> keys to respectively move the cursor to the beginning and end of a line (and using <kbd>Shift</kbd> to select the text if desired).
  
  Also, I have swapped the <kbd>⌘ Command</kbd>/<kbd>⌥ Option</kbd>+<kbd> arrow</kbd> keys behaviour: <kbd>⌘ Command(mapped)</kbd>+<kbd>←</kbd>/<kbd>→</kbd>  now moves the cursor between words, and <kbd>⌥ Option(mapped)</kbd>+<kbd>←</kbd>/<kbd>→</kbd> moves to the start/end of a line (and <kbd>Shift</kbd> with both sets to select the text, if desired). 
  
  This seems to work everywhere in MacOS, except some text editors, like Atom. Atom has its own keymap, so I have also had to replicate this behaviour in the Atom keymap settings. 
* [iTerm2 configuration](iterm2/)
  
  Especially for the colour palette that I really got used to when using Fedora, as well as some key mappings (as iTerm2 doesn't recognise/respect most [custom `DefaultKeyBinding.dict`](macoskeybindings/macoskeybindings.md) settings).
* For my Zsh configuration, see [its own specific repo](https://github.com/lucascosti/zshrc).
