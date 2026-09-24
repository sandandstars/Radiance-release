# Radiance firmware

This repo publishes only the compiled `firmware.bin` for Radiance devices to fetch over OTA.
The source code is kept elsewhere and is not published here.

To publish a new version: build the Radiance ESP-IDF project (`idf.py build`, or the Build button
in VS Code). The build encrypts the firmware and updates this folder's `firmware.bin`
automatically. Then commit and push the updated file from here.
