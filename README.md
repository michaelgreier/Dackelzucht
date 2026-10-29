# Dackelzucht

Ein kleines Drag-and-Drop-Spiel für den Biologieunterricht (Klasse 5/6, Thema „Vom Wolf zum Dackel“).

Die Schülerinnen und Schüler wählen zuerst aus den beiden Familien vom Arbeitsblatt ein Zuchtpaar (Hündin und Rüde). Jedes Paar bekommt vier Nachkommen, aus denen wieder ein neues Zuchtpaar gewählt wird. Ziel ist ein Dackel mit höchstens 29 cm Schulterhöhe. Wer immer die kleinsten Tiere auswählt, schafft es im Idealfall in 4 Generationen.

## Dateien

- `index.html` – das komplette Spiel (HTML, CSS und JavaScript in einer Datei)
- `bilder/` – die Hundebilder, ausgeschnitten aus dem Arbeitsblatt „AB Dackelzucht“
  - `dora.jpg` … `elsbeth.jpg`: die beiden Familien aus Aufgabe 1
  - `stufe1_1.jpg` … `stufe9_4.jpg`: die 9 Größenstufen der Begleitseite (je 4 Varianten)

## Veröffentlichen mit GitHub Pages

1. Neues Repository auf GitHub anlegen und den Inhalt dieses Ordners hochladen.
2. Im Repository unter **Settings → Pages** bei „Branch“ `main` und den Ordner `/ (root)` wählen und speichern.
3. Nach ein bis zwei Minuten ist das Spiel unter `https://<benutzername>.github.io/<repository>/` erreichbar.

Lokal funktioniert es auch: einfach `index.html` im Browser öffnen.

## Bedienung

- Karten mit der Maus oder dem Finger in das Feld „Zuchtpaar“ unten ziehen, oder einfach antippen.
- Eine Karte im Zuchtpaar-Feld antippen, um sie wieder herauszunehmen.
- „Neu starten“ beginnt wieder bei Aufgabe 1.

Die Schulterhöhen sind aus der Bildgröße geschätzt und dienen nur dem Spiel.
