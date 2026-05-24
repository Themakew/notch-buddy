# Privacy

NotchBuddy is designed as a local-first macOS utility. It does not require an account, does not include analytics, and does not upload your shelf files, picked colors, settings, or media history to a NotchBuddy server.

## What NotchBuddy Stores Locally

NotchBuddy may store the following data on your Mac:

- App settings, such as notch sizing, enabled tabs, animation preferences, shelf behavior, media settings, and color picker preferences.
- Shelf items you intentionally add, including file references, links, and text snippets.
- Security-scoped bookmarks for files you add to the shelf, so those files can still be accessed after relaunch.
- Temporary imported copies for files that macOS provides only as short-lived drag items, such as unsaved screenshots.

This data stays on your device unless you explicitly share, drag, copy, or export it.

## Files And Shelf Items

When you drag files into the shelf, NotchBuddy stores a local reference to those files. For reliability, it may create security-scoped bookmarks or local imported copies when macOS gives the app a temporary file that may disappear.

NotchBuddy does not scan your files in the background. It only handles files you add or interact with through the app.

## Clipboard

NotchBuddy may write to the clipboard when you choose actions such as copying a color value, copying text, or dragging/copying shelf content.

NotchBuddy does not monitor your clipboard continuously.

## Color Picker

The color picker samples the pixel color you choose on your screen. Picked colors may be kept in local app state/history so you can reuse or copy them.

NotchBuddy does not upload screenshots or screen contents.

## Media Controls

If you use media features, NotchBuddy may ask macOS for permission to control Music or Spotify through Automation. This is used to:

- Read the current track title, artist, album, playback state, duration, and position.
- Send playback commands such as play, pause, next, previous, and seek.
- Keep the notch media UI in sync.

NotchBuddy should request media permissions only from the welcome flow or the first time you open the Media tab with the notch expanded.

## Apple Music Access

Apple Music library permission is optional. It is used only when needed for media support, such as improving Apple Music artwork and metadata reliability.

If you deny Apple Music access, NotchBuddy should still work for basic media controls where macOS Automation allows it.

## Album Artwork Lookup

When local media apps do not provide artwork reliably, NotchBuddy may use Apple’s public iTunes Search API as a fallback. In that case, the current track title, artist, and album may be sent to Apple to search for matching artwork.

NotchBuddy does not send your full music library. It only looks up the currently playing track when artwork is missing or unusable.

## Network Access

NotchBuddy uses network access only for features that need it, such as fetching missing album artwork from Apple’s public artwork/search services.

NotchBuddy does not use network access for analytics, tracking, advertising, or account sync.

## Sharing

When you choose to share an item, NotchBuddy uses macOS sharing features such as the system share sheet or AirDrop. At that point, the selected item is handled by macOS and the destination you choose.

NotchBuddy does not automatically share shelf contents.

## Permissions

NotchBuddy may request these macOS permissions depending on the features you use:

- Automation for Music and Spotify media control.
- Apple Music access for optional media metadata/artwork support.
- File access for files you add to the shelf.
- Network client access for missing album artwork lookup.
- Screen/color sampling only when using the color picker.

You can revoke permissions in macOS System Settings.

## No Analytics Or Tracking

NotchBuddy does not collect analytics, advertising identifiers, usage telemetry, or personal tracking data.

## Data Removal

To remove data from NotchBuddy:

- Delete shelf items from the shelf.
- Clear or change app settings from Settings.
- Remove the app’s container data from macOS if you want a full local reset.
- Revoke permissions in System Settings > Privacy & Security.

## Contact

For privacy questions, bug reports, or permission concerns, contact the app developer or open an issue in the project repository.
