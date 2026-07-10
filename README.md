# Membrane – Update-Feed

Dieses Repository enthält ausschließlich Update-Binaries und Sparkle-Appcasts
für [Membrane](https://github.com/taniii1234/Membrane) (privates Quell-Repo).

- `beta/appcast.xml` — Beta-Kanal
- `stable/appcast.xml` — Stable-Kanal
- Update-ZIPs liegen als Assets der Sammel-Releases `beta-assets` / `stable-assets`.

Updates sind EdDSA-signiert; die Appcasts werden von `release.sh` im
Quell-Repo erzeugt. Manuelle Änderungen an Appcasts oder Assets machen
Updates ungültig.
