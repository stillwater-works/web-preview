# web-preview – Preview (noindex)

> Statische Landingpage als Vorschau auf GitHub Pages.

Wichtig:
- robots.txt setzt Disallow: /, index.html injiziert <meta name="robots" content="noindex,nofollow">.
- Pflichtangaben (Impressum/Datenschutz) müssen ergänzt und vor Go-live geprüft werden.
- Rollback siehe unten.

## Rollout (Plan)
1. Repo öffentlich anlegen (Name siehe Titel)
2. Dateien aus dieser Version commiten und pushen
3. In den Einstellungen GitHub Pages aktivieren (Source: GitHub Actions)
4. Preview prüfen (noindex, Pflichtangaben, Links/UTM)

## Rollback (Plan)
- GitHub Pages in den Einstellungen deaktivieren
- Revert-Commit, ggf. Repo auf privat setzen oder archivieren
