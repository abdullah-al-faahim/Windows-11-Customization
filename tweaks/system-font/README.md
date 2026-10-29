# Change the Windows system font

Replaces Segoe UI with **JetBrains Mono** across the Windows UI using registry font substitution.

1. Extract `JetBrainsMono-2.304.zip` and install the fonts in `fonts/ttf` (select all → right-click → **Install for all users**).
2. Double-click `ChangeFont.reg` and accept the prompt.
3. Sign out or restart.

To go back to Segoe UI, run `RestoreFont.reg` and restart.

> These files edit `HKLM`. Create a restore point first. Font source: [jetbrains.com/lp/mono](https://www.jetbrains.com/lp/mono/).
