# io.mpv.Mpv.Extension.bdj

Optional Flatpak extension that adds Blu-ray Java (BD-J) menu support to [io.mpv.Mpv](https://flathub.org/apps/io.mpv.Mpv).

It ships:

- OpenJDK 17 JRE
- libbluray BD-J JAR files (must match the libbluray version in the main mpv Flatpak)

## Version sync

When bumping libbluray in `io.mpv.Mpv.yml`, update this extension to the same tarball and sha256 so the JAR names match what `libbluray.so` expects.
