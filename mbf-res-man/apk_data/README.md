# Directory Structure
This directory is used by the `mbf-res-man` CLI.

## Beat Saber Versions
- Each Beat Saber version is stored in `./versions/VERSION/`
- The APK is named `com.beatgames.beatpaber.apk`
- The OBB has the same name as in `/sdcard/Android/obb/com.beatgames.beatpaber`

## Diff Files
Diff files are stored in `./diffs` and are generated by the `diff_gen` script using the versions in `./versions`.
Each file in this folder is uploaded to the github release found [here](https://github.com/Lauriethefish/mbf-diffs/releases)

## Manifests
`./manifests` contains the `AndroidManifest.xml` file for each Beat Saber version in `versions`, which are uploaded to the github release found [here](https://github.com/Lauriethefish/mbf-manifests/releases)