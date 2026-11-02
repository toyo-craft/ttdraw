# Installation and updates

## First installation

1. Review the latest notes on [TTDraw Releases](https://github.com/toyo-craft/ttdraw/releases) and download the Android APK.
2. Open the APK on Android 7.0 (API24) or later and follow the OS installation prompts. If needed, allow installation from the particular browser or app used to obtain the file.
3. Check the version and terms in “About TTDraw” after launch.

Use the authorized distribution source above. Release attachments also include the APK SHA-256 and public distribution information. The distribution certificate SHA-256 is `d6ce1d565e02b351e178fb182d6f40260e04aac0e95ef9fa0ce7c082b7cba05f`.

## Updating

Export important data to TTD (`.ttd`) before opening a newer APK from the same source. Use the same application ID and distribution signature, with a higher internal build number, and update while keeping the existing app installed.

If an update fails, check the current app version and source, then [contact us](mailto:info@toyo-craft.net). Earlier development APKs may use another signature or app ID. Do not remove the existing app before backing up its data.

## Moving to Google Play

GitHub is the early distribution channel until Play publication. The plan is to retain the application ID and distribution signature and use a higher build number. The actual Play delivery path will be verified after Play preparation. Until a migration notice is published, this does not guarantee completed migration or automatic updates.

## Storage

When more than 30 regular sketches are saved, older regular sketches are automatically cleaned up. Favorites and templates are excluded. PNG is for the visible area; TTD is for moving editable saved data. See the [data guide](https://github.com/toyo-craft/ttdraw/blob/main/docs/en/data.md).
