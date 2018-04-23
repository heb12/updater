# Updater
JSON files for information about different versions of Heb12 Desktop. Used for checking for updates.

Heb12 Desktop makes a request to https://heb12.github.io/updater/desktop/VERSION-NUMBER, and then this responds and gives the latest information about the version that they are using. 

The response given is like this:
```
{
  "version": "0.1.0",
  "status": "beta",
  "outdated": false,
  "newest": "0.1.0"
}
```
It states the version requested, the status of that version, whether it is outdated, and what the newest version is. 
