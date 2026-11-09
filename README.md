# Mini Buckets

Mobile-first collection tracker PWA, version 1.0.3.

Features: store/color dropdowns with + New choices, notes, quantity, lid flag, quick +/- quantity buttons, search, store/color/lid filters, sorting, duplicate protection, undo after deletion, blank collection for new users, offline cache, JSON backup/restore with last-export indicator, CSV export, version in header.

## Storage
Saved in this browser's localStorage. Existing inventory is preserved across normal app updates. No automatic cross-device or Google Sheets synchronization. Export a JSON backup before resetting browser data or changing phones; import replaces local inventory on confirmation. Backup timestamp indicates when the export was initiated, not whether the file was successfully saved by the browser.

## Publish
In GitHub Settings > Pages choose Deploy from branch, main, root. App URL: https://markz68.github.io/Mini-Buckets/

## Test
On Android and Windows, confirm header version v1.0.3, existing data, quick quantity changes, store/color/lid filters, add/edit/delete and Undo, new store/color, duplicate warning, JSON/CSV export, backup status, import confirmation, reload and offline operation.
