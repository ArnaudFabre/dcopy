# dcopy

Date copy

Script that copy recursively files containing creation dates to a year/month directory structure.

It has been made to easily save images and videos to a synchronized cloud directory.

Can be put in a cron job for automatic sync.

## Behavior

New files are directly copied if it does not exists.
If it exists, filename_MD5 is created to allow further checks.

## Logs

Logs are created and never removed
You have three logs where you run the scipt : copied.log, already.log and error.log

## Output
. indicates copy
+ indicates copy with MD5
_ indicates already there

A count summary is shown at the end of the script.

## Error files

Error files are copied in tbc subfolder that must be checked.

## OSes

Created first on linux with exif tool dependency (no more tested).
Then improved for mac using mlds and tested.

