# ErstiKit Beamer


Ein schlankes Beamer‑Theme im Stil des Ersti‑Hefts. Brand‑Profiles machen es universell nutzbar.


## Quickstart


1. `config/brand.tex` öffnen und gewünschtes Brand auswählen.
2. `assets/logo.pdf` ersetzen, Farben im Brand anpassen.
3. Inhalte in `content/pages/*.tex` pflegen.
4. Bauen mit `make pdf` oder `latexmk -pdf main.tex`.


## Theme‑Optionen


In `config/brand.tex` via `\eksetup{...}`:
- `title diagonal=true|false` diagonal‑Balken auf der Titelseite
- `accent dot=true|false` Akzentpunkt rechts oben
- `footline=compact|minimal` Fußzeile kompakt oder Standard
- `logo=Pfad/zum/logo.pdf` Logo rechts auf der Titelseite


## Hinweise


- Lange PDFs bitte nicht direkt via `includepdf` in Frames, lieber verlinken oder als QR.
- Für andere Brands kopiere `styles/beamercolortheme-erstikit-default.sty` und passe Farben an.