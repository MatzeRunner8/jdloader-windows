# jdLoader für Windows – Updates

Dieses Repo verteilt zwei Dinge an jdLoader für Windows:

- `hosters.json` (+ `hosters.json.sig`): Hoster-Katalog mit Domains, API-Adressen und weiteren XFileSharing-Hostern.
  Typen: `rapidgator`, `nitroflare`, `xfs`. Neue XFS-Hoster brauchen nur einen Eintrag, keinen neuen Build.
  `version` hochzählen, sonst übernimmt die App die Datei nicht; `minBuild` = älteste App-Build-Nummer, die den Katalog versteht.
- Releases mit dem Tag `v<Version>-build<Nummer>` und den Assets `jdLoader.exe` und `jdLoader.exe.sig`.

Beide Dateien sind mit ECDSA P-256 signiert. Ohne gültige Signatur übernimmt die App nichts.
