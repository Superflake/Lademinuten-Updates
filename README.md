# Lademinuten – Updates

Dieses Repository enthält nur die Dateien, die die Android-App **Lademinuten** für ihre
Update-Prüfung braucht:

- `version.json` – aktuelle Versionsnummer, Prüfsumme und „Was ist neu“
- `Lademinuten-<Version>.apk` – die installierbare App

Die App lädt `version.json` von `https://raw.githubusercontent.com/Superflake/Lademinuten-Updates/HEAD/version.json`.
Der Quellcode liegt in einem separaten Repository. Neue Versionen werden mit
`./android/publish-update.sh` aus dem Quell-Repository hierher veröffentlicht.
