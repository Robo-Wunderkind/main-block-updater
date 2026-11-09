# Robo Wunderkind Main Block Updater

Updates the firmware on **RW2 and RW3 main blocks** that the Robo app can't update. After the update, the main block works with the Robo app again.

## Download

These links always give you the newest version.

| Your computer | Download |
|---|---|
| Windows 10 or 11 | [RoboHotspotUpdater-Windows.exe](https://github.com/Robo-Wunderkind/main-block-updater/releases/latest/download/RoboHotspotUpdater-Windows.exe) |
| Mac with Apple silicon (M1 or later) | [RoboHotspotUpdater-Mac-AppleSilicon.tar.gz](https://github.com/Robo-Wunderkind/main-block-updater/releases/latest/download/RoboHotspotUpdater-Mac-AppleSilicon.tar.gz) |
| Mac with an Intel processor | [RoboHotspotUpdater-Mac-Intel.tar.gz](https://github.com/Robo-Wunderkind/main-block-updater/releases/latest/download/RoboHotspotUpdater-Mac-Intel.tar.gz) |

To check which kind of Mac you have, open the Apple menu and choose **About This Mac**. It lists a **Chip** (Apple silicon) or a **Processor** (Intel).

Nothing else needs to be installed.

## Before you start

- Use a computer with Bluetooth and Wi-Fi, connected to the internet.
- Charge the main block and switch it on.
- Close the Robo app on every phone and tablet nearby, so the main block is free to connect.

## Running it

**Windows**

1. Double-click `RoboHotspotUpdater-Windows.exe`.
2. If Windows shows "Windows protected your PC", click **More info**, then **Run anyway**.

**Mac**

1. Double-click the downloaded `.tar.gz` file to unpack it.
2. Double-click `RoboHotspotUpdater-Mac-…`. It opens in Terminal.
3. If macOS says it can't be opened, go to **System Settings → Privacy & Security** and click **Open Anyway**.
4. When macOS asks whether Terminal may use Bluetooth, click **Allow**.

Then follow the steps on screen. The updater:

1. Finds your main block.
2. Downloads the latest firmware for it.
3. Offers the update methods your main block supports.
4. Checks at the end that the new firmware is running.

During the update, keep the main block switched on and close to the computer.

## If something goes wrong

Each run saves a log file named `robo_update_<date>_<time>.log` next to the updater. Send that file to Robo Wunderkind support; it shows exactly where the update stopped.
