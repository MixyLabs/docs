# Setup meej

The nice thing about meej is that there is no setup at all.

It is a single executable that just needs a config file alongside it.
Everything about the config file is documented inside the default one.
So I don't feel like repeating all of it here again.

Upon starting, meej will scan for available Mixy devices and attempt to connect to the first one it finds.
After connecting, it will operate according to your configuration file.

## Tips

Bluetooth must be enabled **before** starting meej. If Bluetooth gets disabled while meej is running, the app will need to be restarted.

Changes made to the configuration file are automatically detected and applied.

## Browser tabs volume control

Meej supports controlling volume of individual browser tabs. Only for Chromium-based browsers, though.

First you need to install [meej's web extension](https://github.com/MixyLabs/meej-web-ext).
Simply download the zip from latest release and drop it onto your browser's extensions page (`chrome://extensions`).

If you are lucky, as this is experimental, the extension will connect with meej.

Remember that for the extension to work for a given tab it needs to be clicked while this tab is focused.
Instructions for binding tabs to knobs are inside the config file.
