# Android local manifests
These are manifests to be used with the android build system and its repo tool.
They should be placed inside `./repo/local_manifests/`

##### Usage:
Get the manifests
```
curl https://raw.githubusercontent.com/TeamMoskvich/android_local_manifest/lineage-15.1/<DEVICE>.xml > .repo/local_manifests/<DEVICE>.xml
```
Sync the repo to get changes
```
repo sync -j 4 -c
```
