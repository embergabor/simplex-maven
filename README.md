# simplex-maven

A Maven repository, served by GitHub as plain files, for
[simplex-core](https://github.com/embergabor/simplex-core): the Plex connection and player behind Simplex
and PlexVerse. Nothing is built here; `tools/publish.sh` in simplex-core adds each version.

```kotlin
maven("https://raw.githubusercontent.com/embergabor/simplex-maven/main")
```
