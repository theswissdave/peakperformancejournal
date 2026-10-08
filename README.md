# peakperformancejournal.ch

Landingpage für **Das Peak Performance Journal** von David Habluetzel.

## Wie die Seite aktualisiert wird

Jede Änderung in diesem Repository veröffentlicht Netlify automatisch —
meist innerhalb einer Minute. Es muss nichts hochgeladen werden.

## Dateien

| Datei          | Inhalt                                               |
|----------------|------------------------------------------------------|
| `index.html`   | Die ganze Seite: Text, Gestaltung und Formular        |
| `danke.html`   | Bestätigungsseite nach dem Absenden des Formulars     |
| `img/`         | Buchcover und Fotos                                   |
| `netlify.toml` | Einstellungen für den Hoster                          |
| `robots.txt`, `sitemap.xml` | Für Google                               |

## Formular

Das Kontaktformular läuft über **Netlify Forms** — kein externer Dienst.
Die Anfragen stehen im Netlify-Dashboard unter *Forms* und werden zusätzlich
per E-Mail an contact@davidhabluetzel.com geschickt
(Einstellung: Site configuration → Forms → Form notifications).

Das Formular heisst `anfrage`. Felder: Name und E-Mail sind Pflicht,
Firma, Anzahl Exemplare und Nachricht sind freiwillig.
