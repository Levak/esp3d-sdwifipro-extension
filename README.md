Extension for ESP3D v3.x WebUI to interact with custom SD WIFI PRO firmware.

# Setup

1. Flash your SD WIFI PRO with [Async](https://github.com/Levak/sdwifi/tree/async) or [non-Async](https://github.com/tiredboffin/sdwifi) custom firmware
2. Edit [`sdwifi.html`](sdwifi.html#L137) and set the SD WIFI PRO IP address
3. Upload `sdwifi.html` to ESP3D flash
4. In ESP3D configuration, add an extension panel pointing to `sdwifi.html`

# Use cases

- Upload files directly from ESP3D WebUI
- Starting file print directly from ESP3D WebUI, same panel where you uploaded the file
- Managing files and directories
- Uploading several files at once

# TODO list

- Add IP configuration/setting directly in the UI.

