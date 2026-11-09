# Stundenplan

- `update.json`: Die App prüft diese Datei. Ist `version` höher als die installierte, lädt sie die APK aus `apk` und prüft `sha256`.
- `Stundenplan-<Version>.apk`: signierte APK zum Herunterladen.

Neue Version: `sh build.sh` im Stundenplan-Repo, dann `dist/Stundenplan-<Version>.apk` und `dist/update.json` hierher kopieren und auf `main` pushen.
