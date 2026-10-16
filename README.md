# Billables Ledger

A personal hours tracker that runs in the browser and can be added to an iPhone home screen or a Mac Dock.

All entries stay on the device that recorded them, in the browser's own storage. This repository holds only the app's code. No hours or notes are ever sent here.

- **Sync:** tap Send on one device and AirDrop the file, then tap Load on the other. The two devices' data is merged.
- **Passcode (optional):** encrypts the data on the device with a key derived from your passcode (PBKDF2 + AES-GCM). Sync files are encrypted with it too.
- **Offline:** a service worker caches the app's files so it opens without a connection.
