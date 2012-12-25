# 25.12.2012

---

Changed default keybinding to "ctrl+cmd+t" due to global bindings problems 
explained in [issue 5](https://github.com/afterdesign/MacTerminal/issues/5)

---

Added support for iTerm 2. Just go to:
    
```
Sublime Text 2 -> Preferences -> Package Settings -> Macterminal -> Settings - User
```

and add:

```
{
    "terminal"   :  "iterm"
}
```
If you wish you can also change it in Settings - Default.

---

Added full support for opening terminal from sidebar. 
Just right click on file or directory and use "Open in terminal".
For now there is no support for multiple selected files in sidebar.