# GFS in der Eingangsklasse

Infoseite zur GFS in der Eingangsklasse (ab SJ 2026/27) mit einem Reiter für Schüler:innen und einem für Lehrkräfte.

## Inhalt

- `index.html`: die komplette Seite (HTML, CSS und JavaScript in einer Datei)
- `material/`: alle Originaldokumente als PDF/DOCX zum Herunterladen

## Auf GitHub Pages veröffentlichen

1. Auf github.com ein neues Repository anlegen, z. B. `gfs-eingangsklasse`. Es muss **Public** sein.
2. Über **Add file → Upload files** die Datei `index.html`, diese `README.md` und den Ordner `material` hochladen. Zum Schluss auf **Commit changes** klicken.
3. Unter **Settings → Pages** bei „Source“ die Option **Deploy from a branch** wählen, dann Branch `main` und Ordner `/ (root)` einstellen und **Save** klicken.
4. Nach 1–2 Minuten ist die Seite unter `https://<benutzername>.github.io/gfs-eingangsklasse/` erreichbar.
5. Direktlinks: `…/#schueler` öffnet den Schülerbereich, `…/#lehrkraefte` den Lehrkräftebereich.

## Pflege

- Texte lassen sich direkt in `index.html` ändern, die Abschnitte sind kommentiert.
- Neue Version eines Dokuments: Lade die Datei mit **gleichem Namen** in `material/` hoch, dann bleiben alle Links gültig.
- Farben werden ganz oben im `<style>`-Block unter `:root` angepasst.
