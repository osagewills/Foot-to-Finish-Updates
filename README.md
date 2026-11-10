# Foot to Finish updates

Over-the-air test updates for the Foot to Finish watch app (Royal Artisan Technologies).

- `update.json` - what the watches check: newest version for each channel (owner, tester, face), download link and fingerprint (sha256).
- `apk/` - the update files.

The app checks this list every few hours (or from Menu > Check for updates). A watch only installs a file whose
fingerprint matches and which is signed with the app's own key, so saved builds, album and gems are kept.
