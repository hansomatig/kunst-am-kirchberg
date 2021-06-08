# kunst-am-kirchberg

## Aufgaben, Links, Artikel, usw. des nächsten Lernabschnittes
- [x] Markdown verinnerlichen
- [x] vlt. Markdown Tabelle erstellen
- [ ] Dokumentation von liquid, yaml, collections, assets 
- [ ] Einpflegen von Künstlern und Kunstwerken

## Lernziele
- [x] Setup, Git Workflow, Markdown
- [ ] HTML
- [ ] CSS
- [ ] SCSS
- [ ] YAML
- [ ] Layouts
- [ ] Includes
- [ ] Liquid Templates
- [ ] Projektmanagement Basics
- [ ] Git Basics 101: Pull Requests & Merge, Branches, etc.

## Lektionen

**markdown** = Dateiformat
- Umwandlung in html
- Dateiendung `.md` oder `.markdown`
- [Dokumentation](https://daringfireball.net/projects/markdown/basics)

**jekyll** = static site generator 
- Wandelt Content Dateien z.B. Markdown in eine fertige Webseite um

**git** = Versionskontrollsystem 
- `git clone <URL>` -> Herunterladen eines Repositories 
- `git pull` -> Herunterladen des neusten Standes
- `git push` -> Hochladen des neusten Standes
- `git commit -m "<Was habe ich in dieser Version gemacht>"` -> Neuer Zwischenstand abspeichern + Änderungsbeschreibung  

**liquid** = Programmiersprache die Befehle extentgegen nehmen kann und HTML schreibt
- `{% Befehl %}` -> Entgegennehmen eines Befehls wie z.B. for ... in ...
- {{ Inhalt }} -> schreibt den Inhalt als HTML aus

**yaml** = Variablen-Ordungssystem
- `Varibale: Inhalt der Variable` -> Speichern von einer Variable oder Konstante
- `---` -> öffnet bzw. schließt den Teil in dem mit YAML geschrieben wird

**collection** = Ansammlung an Vorlagen // wird in config verwendet

**asset** = Vorlage
- wird in YAML geschrieben
