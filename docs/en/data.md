# Storage, backup, and migration

Sketches are stored on the device. The current app has no automatic synchronization to the Provider's cloud and no login or payment contract that enables such storage.

## A limit of 30 regular sketches

Automatic cleanup applies to regular, non-favorite sketches above the limit of 30. After a save or import is committed, the oldest eligible sketches by save date are cleaned up. Favorites, templates, and unreadable saved entries are excluded. Merely reading existing data does not trigger bulk cleanup.

## Back up with TTD

- Choose “Export” from the list menu to save all stored data in one TTD (`.ttd`) file.
- The file contains regular and favorite sketches, templates, and corresponding image materials. Settings such as language and Undo history are not transferred.
- Export important data regularly to a safe location outside the app. Also verify that the backup can be imported when needed.
- “Import” appends to existing data. Importing the same file again may create duplicates. If an import exceeds the 30-regular-sketch limit, review the cleanup count and confirmation before committing.

## PNG and sharing

PNG captures the currently visible canvas area. It is not a backup of the entire editable document outside the viewport. Use TTD for re-editing and saved-data migration. Manage exported files, shared copies, and clipboard contents at their respective destinations.

Uninstalling the app or clearing OS app data may remove on-device data. OS-provided backup is separate from cloud storage by the Provider. Review the [Privacy Policy](https://github.com/toyo-craft/ttdraw/blob/main/docs/en/privacy.md).

Send non-public data inquiries to [info@toyo-craft.net](mailto:info@toyo-craft.net), not a public issue.
