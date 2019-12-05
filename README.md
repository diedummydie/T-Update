# T-Update

This is an unofficial [Tales of Maj'Eyal](https://te4.org) updater for the non-Steam macOS version of the game (which doesn't update on its own). This tool keeps your addons (like the official Ashes, Embers, and Cults DLCs) intact across updates. It will also install the game if it isn't present.

[Click here to **Download**](https://github.com/diedummydie/ToME-Update/releases/download/1.0/ToME-Update.dmg). Open the file, then drag and drop to install.
![Installation](https://github.com/diedummydie/ToME-Update/blob/master/etc/dmg.png)

It stays next to the game for quick access.
![T-Engine and T-Update icons](https://github.com/diedummydie/ToME-Update/blob/master/etc/icon.png)

Launch the updater, and the rest is automatic.
![Updating](https://github.com/diedummydie/ToME-Update/blob/master/etc/updating.png)

No time or bandwidth are wasted when you're already up-to-date.
![Current](https://github.com/diedummydie/ToME-Update/blob/master/etc/updated.png)

### What's under the hood?

This tool gets ToME updates directly from <https://te4.org>, and doesn't alter them or your game in any way. Your game itself will still be the official, unmodified version. It's essentially a shell script, bundled into an app for convenience.

![vim](https://github.com/diedummydie/ToME-Update/blob/master/etc/vim.png)

If you'd like to see how it works, the core functionality is in [this file (tome_update)](https://github.com/diedummydie/ToME-Update/blob/master/T-Update.app/Contents/Resources/tome_update), and if you enjoy working in the Terminal, that file is all you need. It uses absolute paths, so you can put it in `/usr/local/bin`, `$HOME`, or wherever you want. Just `chmod +x` it to make it executable. If you don't put it somewhere in your `$PATH`, remember to prepend it with dot-slash so your shell knows to look for it in the current folder. (`./tome_update`)

### Disclaimer

This is an unofficial, fan-made project, not affiliated with [DarkGod](https://www.patreon.com/darkgodone), the creator of ToME and T-Engine. The program is provided "as-is" without warranty of any kind.
