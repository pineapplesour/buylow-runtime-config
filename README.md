# Buylow Runtime Config

This repository hosts the public runtime configuration document used by Buylow demo clients.

## Files

- `runtime-config.json`: current API base URL, optional announcement text, and client policy knobs.

## How to update

Edit `runtime-config.json` and commit the change. Fresh Buylow app launches will fetch the new config and use the updated `apiBaseUrl` without requiring an APK rebuild.
