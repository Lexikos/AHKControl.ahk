# AHKControl

Control running AutoHotkey scripts by using a hotkey and menu.

Features:
  - Activate any of the standard tray menu options for a script, even if its tray menu has been customized.
  - The menu is keyboard-accessible. For example, use `#q`, `1`, `v` to view variables for the most recent script.
  - If possible (on older OS versions), the tray icons are retrieved. Otherwise, each script can set its own icon using WM_SETICON with its main window (A_ScriptHwnd).

Requires AutoHotkey v1.1 (probably v1.1.23+), but can control any AutoHotkey version.
