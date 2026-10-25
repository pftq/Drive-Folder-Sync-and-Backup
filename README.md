# Drive-Folder-Sync-and-Backup
Backing up and syncing just specific folders to Google Drive across multiple computers (and being able to map to specific folders on Drive).

This was functionality that Google Drive Backup and Sync (desktop) used to have but took out for no reason.  It lets you backup and sync specific folders from your computer to Google Drive across multiple computers (not just for "My Computer").  In addition, I took it a step further to let you map directly where in Google Drive it backs up to, instead of dumping everything in the root folder like the original app did.  You can also set certain computers to be upload-only so that they just push new files without downloading the whole folder.  It's also just way more minimalistic and doesn't attach to right-click context menus or anything (which often slow-down Windows Explorer waiting on the Drive app).

I mainly made this for myself after Google Drive Backup and Sync (the official one) disabled most of the backup/sync functionality I depended on.  Since I mainly use this only to back up to Drive, the safety checks mainly focus on never deleting or replacing local files without confirmation (which differs from official Google Drive app that will go either direction without prompting).  There may be bugs, so I recommend testing on smaller folders or new folders first if you are migrating from another setup.

<img width="1072" height="998" alt="image" src="https://github.com/user-attachments/assets/c4fc55cc-f0d5-489c-a071-150115cb989f" />

The only catch here is that Google requires a Google Key from Google Cloud to use their API.  I would include mine for free, but they are capped at 100 users unfortunately.  Instructions are linked in the app.


Credits to rclone for the base app and functionality that this sits on top of.
