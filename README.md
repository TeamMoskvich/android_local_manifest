# Android local manifests
These are manifests to be used with the android build system and it's repo tool.
They should be placed inside `./repo/local_manifests/`

##### Ussage:
Get the manifests
```
curl 
https://raw.githubusercontent.com/TeamMoskvich/android_local_manifest/lineage-15.1/<DEVICE>.xml > .repo/local_manifests/
```
Sync the repo to get changes
```
repo sync -j 4 -c
```
