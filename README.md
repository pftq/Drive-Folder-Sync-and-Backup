# Drive-Folder-Sync-and-Backup
Backing up and syncing just specific folders to Google Drive (and being able to map what folders on Drive).

This was functionality that Google Drive Backup and Sync (desktop) used to have but took out for no reason.  It lets you backup and sync specific folders from your computer to Google Drive.  In addition, I took it a step further to let you map directly where in Google Drive it backs up to, instead of dumping everything in the root folder like the original app did.  Lastly, since you can control the specific folders to backup and where to map to in Google Drive, this means you can have multiple computers syncing to the same Google Drive folders, especially useful for keeping files on home PC and travel laptop in sync.

I mainly made this for myself after Google Drive Backup and Sync (the official one) disabled most of the backup/sync functionality I depended on.  There may be bugs, so I recommend testing on smaller folders or new folders first if you are migrating from another setup.

<img width="1072" height="998" alt="image" src="https://github.com/user-attachments/assets/c4fc55cc-f0d5-489c-a071-150115cb989f" />

The only catch here is that Google requires a Google Key from Google Cloud to use their API.  I would include mine for free, but they are capped at 100 users unfortunately.  Instructions are linked in the app.


Credits to rclone for the base app and functionality that this sits on top of.
