# Third-party notices

The Robo Wunderkind Main Block Updater includes the components below. Each is licensed under its own terms; follow the links for the full license text and source. The Robo Wunderkind license ([LICENSE](LICENSE)) does not limit any right these licenses give you.

Versions are those in the current builds.

## All platforms

| Component | Version | License | Source |
|---|---|---|---|
| Python | 3.12.14 | PSF-2.0 | https://www.python.org/ — license: https://docs.python.org/3.12/license.html |
| OpenSSL (bundled with Python) | 3.5.8 | Apache-2.0 | https://www.openssl.org/ |
| libffi (bundled with Python) | | MIT | https://github.com/libffi/libffi |
| zlib (bundled with Python) | | zlib | https://zlib.net/ |
| bleak | 3.1.0 | MIT | https://github.com/hbldh/bleak |
| certifi | 2026.10.23 | MPL-2.0 | https://github.com/certifi/python-certifi |
| PyInstaller bootloader | 6.22.3 | GPL-2.0-or-later with the PyInstaller bootloader exception | https://github.com/pyinstaller/pyinstaller |

**certifi** is used unmodified and is covered by the Mozilla Public License 2.0 (https://mozilla.org/MPL/2.0/). Its source code is available at https://github.com/certifi/python-certifi.

**The PyInstaller bootloader** runs the bundled Python program. Its license exception allows it to be distributed with programs under any license (https://github.com/pyinstaller/pyinstaller/blob/develop/COPYING.txt).

## Windows build

| Component | Version | License | Source |
|---|---|---|---|
| winrt-runtime | 4.1.0 | MIT | https://github.com/pywinrt/pywinrt |
| winrt-Windows.Devices.Bluetooth, .Bluetooth.Advertisement, .Bluetooth.GenericAttributeProfile, .Enumeration, .Radios, winrt-Windows.Foundation, .Foundation.Collections, winrt-Windows.Storage.Streams | 10.0.28000.2957 | MIT | https://github.com/pywinrt/pywinrt |

## Mac builds

| Component | Version | License | Source |
|---|---|---|---|
| pyobjc-core | 13.0 | MIT | https://github.com/ronaldoussoren/pyobjc |
| pyobjc-framework-Cocoa, -CoreBluetooth, -libdispatch | 13.0 | MIT | https://github.com/ronaldoussoren/pyobjc |
