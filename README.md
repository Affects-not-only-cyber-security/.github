# .github

Organisationsprofil der Anocs KG auf GitHub und gemeinsame Vorgaben für alle Repositories der
Organisation.

| Datei | Wirkung |
|---|---|
| [`profile/README.md`](profile/README.md) | erscheint auf der Übersichtsseite der Organisation |
| [`SECURITY.md`](SECURITY.md) | gilt für jedes Repository der Organisation ohne eigene `SECURITY.md` |
| [`.github/CODEOWNERS`](.github/CODEOWNERS) | Änderungen an diesem Repository gibt der Inhaber frei |

## Regeln für alle Repositories

- `main` enthält nur freigegebene Stände. In öffentlichen Repositories ändert sich `main` nur
  über Pull Requests.
- Rechtstexte und Vertragsvorlagen haben Markdown als Quelle. Fassungen werden nach Datum getaggt
  (`vJJJJ.MM.N`), Websites nach [SemVer](https://semver.org/lang/de/).
- Jedes Repository führt ein Änderungsprotokoll nach [Keep a Changelog](https://keepachangelog.com/de/1.1.0/).
- Jedes Repository nennt in `.github/CODEOWNERS`, wer Änderungen freigibt.
- Zugangsdaten und Kundendaten gehören in kein Repository.
