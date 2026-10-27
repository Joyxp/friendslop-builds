# Night Shift at the Liminal Mart: tester builds

Co-op horror-lite for 1–4 players. Restock a store that rearranges itself when nobody's looking.

## Install (once)

Go to **[Releases → Latest](https://github.com/Joyxp/friendslop-builds/releases/latest)** and download:

- **Mac:** `NightShift-mac.zip`. Unzip, move **Night Shift.app** to Applications, and double-click it.
  macOS will block it the first time (it isn't signed). Go to **System Settings → Privacy & Security** and click **Open Anyway**.
- **Windows:** `NightShift-windows.zip`. Unzip and run `NightShift.exe`.
  If you see "Windows protected your PC", click **More info → Run anyway**.

## Updates are automatic

Every time you open the game, it checks for a new build. If there is one, it downloads it
(a few MB) and restarts itself. The build number is shown at the bottom of the main menu,
and everyone in a game should be on the same build.

## Playing together

One person clicks **Host a shift**; everyone else types the host's IP address and clicks **Join a shift**.
On the same Wi-Fi, use the host's local IP. Otherwise, everyone installs [Tailscale](https://tailscale.com)
and uses the host's `100.x.x.x` address.

Controls: WASD move · mouse look · Shift sprint · E interact / ring up · Q refuse service · Esc free the mouse.
